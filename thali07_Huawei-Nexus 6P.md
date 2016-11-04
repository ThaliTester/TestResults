#### Test 924157951a8d3a7_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 22:30:40.641  3983  4115 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-04 22:30:40.727  3983  4115 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-04 22:30:41.110  5592  5592 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 22:30:41.116  5592  5592 D AndroidRuntime: CheckJNI is OFF
11-04 22:30:41.140  5592  5592 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 22:30:41.172  5592  5592 I Radio-JNI: register_android_hardware_Radio DONE
11-04 22:30:41.186  5592  5592 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 22:30:41.189   928  3057 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 22:30:41.209  5592  5592 D AndroidRuntime: Shutting down VM
11-04 22:30:41.220  3841  3851 W SearchService: Abort, client detached.
11-04 22:30:41.230  3841  3841 I HotwordDetector: Closing mic
11-04 22:30:41.230  3841  4104 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@516e45
11-04 22:30:41.231  3841  4112 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 22:30:41.245   928  3056 I ActivityManager: Start proc 5601:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 22:30:41.316   511  4114 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 22:30:41.318   511  4114 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 22:30:41.324   511  4114 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 22:30:41.324   511  4114 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 22:30:41.325   511  2894 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 22:30:41.327  3841  4111 I MicroRecognitionRnrImpl: Detection finished
11-04 22:30:41.327  3841  4107 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 22:30:41.344  5601  5601 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 22:30:41.370  5601  5601 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-04 22:30:41.428  5601  5601 I LibraryLoader: Time to load native libraries: 53 ms (timestamps 8783-8836)
11-04 22:30:41.428  5601  5601 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 22:30:41.464  5601  5601 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d77ddb}
,11-04 22:30:41.464  5601  5601 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 22:30:41.465  5601  5601 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 22:30:41.468  5601  5601 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 22:30:41.468  5601  5601 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 22:30:41.527  5601  5601 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 22:30:41.535  5601  5601 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 22:30:41.535  5601  5601 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 22:30:41.536  5601  5601 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 22:30:41.536  5601  5601 I Adreno  : Build Date                       : 12/06/15
11-04 22:30:41.536  5601  5601 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 22:30:41.536  5601  5601 I Adreno  : Local Branch                     : mybranch17112971
11-04 22:30:41.536  5601  5601 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 22:30:41.536  5601  5601 I Adreno  : Remote Branch                    : NONE
11-04 22:30:41.536  5601  5601 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 22:30:41.577   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53e893d:true
,11-04 22:30:41.615   734   734 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[16822]" dev="sockfs" ino=16822 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 22:30:41.615   734   734 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[16822]" dev="sockfs" ino=16822 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 22:30:41.625  5601  5601 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 22:30:41.635  5601  5601 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 22:30:41.661  5601  5638 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 22:30:41.658   733   733 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33116]" dev="sockfs" ino=33116 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 22:30:41.658   733   733 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33116]" dev="sockfs" ino=33116 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 22:30:41.661   939   939 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[23277]" dev="sockfs" ino=23277 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 22:30:41.661   939   939 W Binder_2: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[23277]" dev="sockfs" ino=23277 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:30:41.667  5601  5625 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 22:30:41.700  5601  5638 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 22:30:41.781  3057  3057 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[29492]" dev="sockfs" ino=29492 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:30:41.781  3057  3057 W Binder_4: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[29492]" dev="sockfs" ino=29492 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 22:30:41.785  3056  3056 W Binder_3: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[29491]" dev="sockfs" ino=29491 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 22:30:41.785  3056  3056 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[29491]" dev="sockfs" ino=29491 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:30:41.784   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +558ms
,11-04 22:30:41.786  3546  3546 I Keyboard.Facilitator: onFinishInput()
,11-04 22:30:41.829  5601  5601 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5601
,11-04 22:30:41.938  5601  5601 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 22:30:42.134  5601  5640 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -583272144
,11-04 22:30:42.138  5601  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 22:30:42.138  5601  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 22:30:42.138  5601  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 22:30:42.138  5601  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 22:30:42.138  5601  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 22:30:42.138  5601  5640 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecd324e added. We now have 1 listener(s)
,11-04 22:30:42.142  5601  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 22:30:42.143  5601  5640 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 22:30:42.143  5601  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:30:42.144  5601  5640 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-04 22:30:42.146  5601  5640 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f200105 added. We now have 1 listener(s)
,11-04 22:30:42.146  5601  5640 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:30:42.153   928  2855 D WifiService: New client listening to asynchronous messages
,11-04 22:30:42.154  5601  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 22:30:42.154  5601  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 22:30:42.155  5601  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-04 22:30:42.155  5601  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 22:30:42.155  5601  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-04 22:30:42.155  5601  5640 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-04 22:30:42.155  5601  5640 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-04 22:30:42.156  5601  5640 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 22:30:42.288  5601  5601 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 22:30:42.682  5601  5610 I art     : Background sticky concurrent mark sweep GC freed 76757(7MB) AllocSpace objects, 16(1076KB) LOS objects, 25% free, 24MB/32MB, paused 3.813ms total 334.356ms
,11-04 22:30:42.850   928  2846 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 22:30:43.565  5601  5610 I art     : Background partial concurrent mark sweep GC freed 59204(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.880ms total 107.184ms
,11-04 22:30:43.659  5601  5649 W jxcore-log: Initializing JXcore engine
,11-04 22:30:43.659  5601  5649 W jxcore-log: JXcore engine is ready
,11-04 22:30:43.681  5649  5649 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11502 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-04 22:30:43.681  5649  5649 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[14371]" dev="sockfs" ino=14371 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-04 22:30:43.681  5649  5649 W Thread-62: type=1400 audit(0.0:113): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-04 22:30:43.681  5649  5649 W Thread-62: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33085]" dev="sockfs" ino=33085 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 22:30:43.691  5601  5649 W jxcore-log: Starting JXcore engine
,11-04 22:30:43.741  5601  5649 W jxcore-log: Platform android
11-04 22:30:43.741  5601  5649 W jxcore-log: 
,11-04 22:30:43.741  5601  5649 W jxcore-log: Process ARCH arm
11-04 22:30:43.741  5601  5649 W jxcore-log: 
,11-04 22:30:43.926  5601  5649 I jxcore-log: JXcore Cordova bridge is ready!
11-04 22:30:43.926  5601  5649 I jxcore-log: 
,11-04 22:30:43.926  5601  5649 W jxcore-log: JXcore engine is started
,11-04 22:30:43.937  5601  5640 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 22:30:43.942  5601  5601 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 22:30:44.759  3484  3484 I ConfigService: onDestroy
,11-04 22:30:45.859   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:30:46.235   928  3700 I ActivityManager: Killing 5302:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-04 22:30:46.860   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:30:47.861   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:30:48.862   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:30:49.864   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:30:50.864   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 22:30:53.579  5601  5649 I jxcore-log: 2016-11-04 21:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 22:30:53.579  5601  5649 I jxcore-log: 
,11-04 22:30:53.581  5601  5649 I jxcore-log: 2016-11-04 21:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 22:30:53.581  5601  5649 I jxcore-log: 
,11-04 22:30:53.587  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 22:30:53.587  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 22:30:53.590  5601  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 22:30:53.592  5601  5649 I jxcore-log: 2016-11-04 21:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-04 22:30:53.592  5601  5649 I jxcore-log: 
,11-04 22:30:53.593  5601  5649 I jxcore-log: 2016-11-04 21:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 22:30:53.593  5601  5649 I jxcore-log: 
,11-04 22:30:53.839  5601  5649 I jxcore-log: 2016-11-04 21:30:53 - DEBUG UnitTest_app: 'Running unit tests'
11-04 22:30:53.839  5601  5649 I jxcore-log: 
,11-04 22:30:53.840  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 22:30:53.840  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74331fb added. We now have 2 listener(s)
11-04 22:30:53.841  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:30:53.841  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:30:53.841  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:30:53.841  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:30:53.841  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f8f218 added. We now have 2 listener(s)
11-04 22:30:53.841  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:30:53.842  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 22:30:53.843  5601  5649 D executeNativeTests: Running unit tests
,11-04 22:30:53.881  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 22:30:53.882  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 added. We now have 3 listener(s)
11-04 22:30:53.882  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:30:53.882  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:30:53.882  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:30:53.882  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:30:53.882  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 added. We now have 3 listener(s)
11-04 22:30:53.882  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:30:53.883  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 22:30:53.885  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 22:30:53.885  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 22:30:53.885  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 22:30:53.885  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 22:30:53.885  5601  5649 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-04 22:30:53.886  5601  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 22:30:53.886  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 22:30:53.886  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 22:30:53.886  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 22:30:53.886  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 22:30:53.886  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:30:53.886  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:30:53.886  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:30:53.886  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 22:30:53.887  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:30:53.887  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:30:53.887  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 removed from the list
11-04 22:30:53.887  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:30:53.887  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 removed from the list
11-04 22:30:53.887  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:30:53.887  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.888  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.888  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:53.888  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.888  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:30:53.888  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:30:53.888  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:30:53.888  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:30:53.889  5601  5649 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 22:30:53.889  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:30:53.889  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:30:53.889  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:30:53.889  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:30:53.889  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:30:53.889  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:30:53.889  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:30:53.889  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:30:53.889  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:30:53.889  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.890  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.890  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.890  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:53.890  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:30:53.890  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:30:53.890  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:30:53.890  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 22:30:53.892  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 22:30:53.893  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-04 22:30:53.893  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:30:53.893  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:30:53.893  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:30:53.893  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:30:53.893  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:30:53.893  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:30:53.893  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:30:53.893  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:30:53.894  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:30:53.894  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.894  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:53.894  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.894  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.894  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 22:30:53.894  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:30:53.894  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:30:53.894  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:30:53.895  5601  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-04 22:30:53.896  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:30:53.896  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 22:30:53.906  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 22:30:53.910  5601  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 22:30:53.910  5601  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 22:30:53.910  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 22:30:53.910  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 22:30:53.910  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 22:30:53.910  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:30:53.910  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 22:30:53.914  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:30:53.915  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 22:30:53.915  5601  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 22:30:53.915  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 22:30:53.917  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:30:53.918  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.918  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 22:30:53.918  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 22:30:53.919  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 22:30:53.919  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 22:30:53.920  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-04 22:30:53.921  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 22:30:53.921  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.921  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 22:30:53.921  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 22:30:53.921  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-04 22:30:53.921  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 22:30:53.921  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.922  5601  5649 D BluetoothAdapter: STATE_ON
,11-04 22:30:53.924  4563  4774 D BtGatt.GattService: registerClient() - UUID=cc0df49a-0f8c-4a4e-821f-2dad2f5d792b
,11-04 22:30:53.924  4563  4623 D BtGatt.GattService: onClientRegistered() - UUID=cc0df49a-0f8c-4a4e-821f-2dad2f5d792b, clientIf=5
,11-04 22:30:53.925  5601  5612 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 22:30:53.926  4563  4576 D BtGatt.GattService: start scan with filters
,11-04 22:30:53.933  4563  4626 D BtGatt.ScanManager: handling starting scan
11-04 22:30:53.933  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 22:30:53.933  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.933  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-04 22:30:53.933  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.933  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 22:30:53.933  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 22:30:53.933  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:30:53.934  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 22:30:53.934  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-04 22:30:53.934  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 22:30:53.934  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:30:53.934  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.934  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 22:30:53.934  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 22:30:53.934  4563  4626 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
11-04 22:30:53.934  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.934  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:53.934  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:53.935  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:30:53.935  5601  5649 I io.jxcore.node.ConnectionHelper: start: OK
,11-04 22:30:53.939  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 22:30:53.940  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:30:53.940  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:30:53.941  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:30:53.941  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:30:53.941  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:30:53.942  4563  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 22:30:53.942  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:30:53.943  4563  4626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 22:30:53.949  4563  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 22:30:53.949  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:30:53.950  4563  4626 D BtGatt.ScanManager: Starting BLE batch scan
11-04 22:30:53.950  4563  4626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 22:30:53.961  4563  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 22:30:53.961  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:30:53.966  4563  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 22:30:53.967  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:30:54.226   928   941 I ActivityManager: Killing 5315:com.android.chrome/u0a39 (adj 15): empty #17
,11-04 22:30:54.321   928   938 I ActivityManager: Start proc 5652:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-04 22:30:54.344  3841  5650 W CronetSyncConnectionRcs: Upload content type not set.
,11-04 22:30:54.358  5652  5652 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-04 22:30:54.415  5652  5666 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-04 22:30:54.430  4787  4817 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 22:30:54.432  4787  4787 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 22:30:54.442  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 22:30:54.442  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:30:54.442  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 22:30:54.481  5652  5666 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-04 22:30:54.513  5652  5666 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-04 22:30:54.536  5652  5652 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-04 22:30:54.549  5679  5679 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads228447566.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads228447566.dex
,11-04 22:30:54.579  5679  5679 I dex2oat : dex2oat took 31.048ms (threads: 2) arena alloc=200KB java alloc=37KB native alloc=1258KB free=1045KB
,11-04 22:30:54.634  5652  5652 W InstanceID/Rpc: Found 10012
,11-04 22:30:54.660  4563  4563 D BtGatt.ScanManager: awakened up at time 92068
,11-04 22:30:54.661  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:30:54.670  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-04 22:30:54.670  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:30:54.670  4563  4623 D BtGatt.GattService: current time is 92078147550
11-04 22:30:54.670  4563  4623 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 22:30:54.671  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 22:30:54.672  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-04 22:30:54.672  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 22:30:54.675  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 3. Current thread: Thread[main,5,main], id: 1
,11-04 22:30:54.675  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-90, mTimestampNanos=92028466873}
11-04 22:30:54.676  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-90, mTimestampNanos=92028466873}
11-04 22:30:54.676  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
11-04 22:30:54.676  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-04 22:30:54.677  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=91478466873}
11-04 22:30:54.677  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=91478466873}
11-04 22:30:54.677  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
11-04 22:30:54.677  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-04 22:30:54.677  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=91978466873}
11-04 22:30:54.677  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-84, mTimestampNanos=91978466873}
,11-04 22:30:54.690   928   938 I ActivityManager: Killing 5177:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 22:30:54.759  3484  5734 I VacuumService: Vacuum at: now=1478295054759 tag=VacuumService
,11-04 22:30:55.177  4563  4563 D BtGatt.ScanManager: awakened up at time 92585
,11-04 22:30:55.179  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:30:55.202  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-04 22:30:55.203  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:30:55.203  4563  4623 D BtGatt.GattService: current time is 92611045051
11-04 22:30:55.203  4563  4623 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-04 22:30:55.204  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 22:30:55.204  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 22:30:55.206  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,11-04 22:30:55.206  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=92511604583}
,11-04 22:30:55.207  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=92511604583}
11-04 22:30:55.207  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
,11-04 22:30:55.207  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-04 22:30:55.208  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=92411604583}
11-04 22:30:55.208  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=92411604583}
11-04 22:30:55.208  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
,11-04 22:30:55.208  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-04 22:30:58.940  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:30:58.940  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 22:30:58.940  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 22:30:58.940  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:30:58.941  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 22:30:58.941  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 22:30:58.941  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 22:30:58.941  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 22:30:58.941  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 22:30:58.941  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 22:30:58.942  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:58.942  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:58.942  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.942  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-04 22:30:58.943  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.944  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:30:58.946  4563  4575 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 22:30:58.949  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 22:30:58.949  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-04 22:30:58.951  5601  5649 D BluetoothAdapter: STATE_ON
,11-04 22:30:58.954  4563  4774 D BtGatt.GattService: stopScan() - queue size =1
,11-04 22:30:58.955  4563  4563 D BtGatt.ScanManager: awakened up at time 96363
,11-04 22:30:58.956  4563  4576 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 22:30:58.958  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 22:30:58.958  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.958  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 22:30:58.958  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.960  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:58.960  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.960  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.960  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 22:30:58.961  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.961  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.961  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:30:58.961  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 22:30:58.962  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 22:30:58.963  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:30:58.963  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:58.967  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:58.967  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 22:30:58.967  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:58.968  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:30:58.968  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:30:58.968  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 22:30:58.968  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 22:30:58.968  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:30:58.968  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:30:58.968  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:30:58.968  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 22:30:58.968  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:30:58.968  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.968  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:30:58.969  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 22:30:58.969  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:30:58.969  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:30:58.969  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 22:30:58.969  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 22:30:58.969  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.969  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.969  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 22:30:58.970  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.972  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.972  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.973  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.973  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:30:58.973  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:30:58.974  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-04 22:30:58.974  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:30:58.974  4563  4623 D BtGatt.GattService: current time is 96382349228
11-04 22:30:58.974  4563  4623 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -75, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 22:30:58.975  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 22:30:58.976  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 22:30:58.976  4563  4623 E BtGatt.ContextMap: Context not found for ID 5
,11-04 22:30:58.988  4563  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 22:30:58.988  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:30:58.988  4563  4626 D BtGatt.ScanManager: stopping BLe Batch
,11-04 22:30:58.997  4563  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 22:30:58.997  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:30:58.997  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:30:59.006  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 22:30:59.006  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:30:59.474  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 22:31:03.972  5601  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 22:31:03.978  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 22:31:03.978  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 22:31:03.991  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 22:31:03.994  5601  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 22:31:03.995  5601  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 22:31:03.995  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:31:03.995  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 22:31:03.995  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 22:31:03.995  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:31:03.995  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 22:31:03.998  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:31:04.000  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 22:31:04.000  5601  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 22:31:04.000  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 22:31:04.001  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:04.005  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.005  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 22:31:04.006  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 22:31:04.006  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 22:31:04.006  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 22:31:04.010  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.011  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 22:31:04.011  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 22:31:04.011  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 22:31:04.011  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 22:31:04.011  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.011  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:31:04.014  4563  4776 D BtGatt.GattService: registerClient() - UUID=994c3319-1d97-4f31-9ab1-cff144650edb
11-04 22:31:04.015  4563  4623 D BtGatt.GattService: onClientRegistered() - UUID=994c3319-1d97-4f31-9ab1-cff144650edb, clientIf=5
11-04 22:31:04.015  5601  5641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 22:31:04.015  4563  4575 D BtGatt.GattService: start scan with filters
,11-04 22:31:04.018  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 22:31:04.018  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.018  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 22:31:04.018  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.018  4563  4626 D BtGatt.ScanManager: handling starting scan
11-04 22:31:04.018  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 22:31:04.018  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 22:31:04.018  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.018  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 22:31:04.018  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 22:31:04.018  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.019  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.019  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-04 22:31:04.020  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 22:31:04.020  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.022  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.022  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:31:04.023  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.023  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.023  5601  5649 I io.jxcore.node.ConnectionHelper: start: OK
11-04 22:31:04.023  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.024  4563  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 22:31:04.025  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.025  4563  4626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 22:31:04.027  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:04.027  5601  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 22:31:04.027  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:04.027  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 22:31:04.027  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:31:04.027  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 22:31:04.027  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:04.027  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 22:31:04.028  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.028  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.028  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-04 22:31:04.028  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.028  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:31:04.029  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 22:31:04.029  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 22:31:04.029  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 22:31:04.029  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:04.029  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.029  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.029  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 22:31:04.029  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.030  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:31:04.030  4563  4576 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 22:31:04.030  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-04 22:31:04.031  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:31:04.031  4563  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 22:31:04.031  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.031  4563  4776 D BtGatt.GattService: stopScan() - queue size =1
11-04 22:31:04.031  4563  4626 D BtGatt.ScanManager: Starting BLE batch scan
11-04 22:31:04.031  4563  4626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 22:31:04.032  4563  4774 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 22:31:04.032  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 22:31:04.032  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.032  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 22:31:04.032  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-04 22:31:04.033  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 22:31:04.033  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:31:04.034  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.034  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.035  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:31:04.035  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.035  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.035  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:04.035  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:31:04.035  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:31:04.035  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 22:31:04.035  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:31:04.035  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:04.035  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 22:31:04.035  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:04.035  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.035  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:04.035  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 22:31:04.035  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:04.035  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 22:31:04.035  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:04.035  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.035  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 22:31:04.035  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.035  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 22:31:04.036  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.037  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.037  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.037  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.037  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.037  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:31:04.037  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.038  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.038  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.038  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.039  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:04.039  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:04.039  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:04.039  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:04.039  5601  5649 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-04 22:31:04.042  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 22:31:04.042  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 22:31:04.043  4563  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 22:31:04.043  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 22:31:04.049  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 22:31:04.049  4563  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 22:31:04.049  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.050  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:31:04.051  5601  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 22:31:04.051  5601  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 22:31:04.051  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:31:04.052  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 22:31:04.052  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 22:31:04.052  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:31:04.052  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 22:31:04.054  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:04.055  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 22:31:04.056  5601  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 22:31:04.056  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 22:31:04.056  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:04.056  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 22:31:04.056  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.056  4563  4623 E BtGatt.ContextMap: Context not found for ID 5
11-04 22:31:04.058  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.059  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 22:31:04.059  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 22:31:04.059  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-04 22:31:04.059  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-04 22:31:04.062  4563  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 22:31:04.062  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.063  4563  4626 D BtGatt.ScanManager: stopping BLe Batch
11-04 22:31:04.063  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.063  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 22:31:04.063  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 22:31:04.064  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 22:31:04.064  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 22:31:04.064  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:04.064  5601  5649 D BluetoothAdapter: STATE_ON
,11-04 22:31:04.066  4563  4776 D BtGatt.GattService: registerClient() - UUID=ece8b013-8c52-48c9-88dd-8150bcf6ae85
11-04 22:31:04.066  4563  4623 D BtGatt.GattService: onClientRegistered() - UUID=ece8b013-8c52-48c9-88dd-8150bcf6ae85, clientIf=5
,11-04 22:31:04.067  5601  5641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 22:31:04.067  4563  4576 D BtGatt.GattService: start scan with filters
11-04 22:31:04.068  4563  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 22:31:04.068  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.068  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 22:31:04.069  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 22:31:04.069  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:04.069  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-04 22:31:04.069  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.070  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 22:31:04.070  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 22:31:04.070  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.070  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 22:31:04.070  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 22:31:04.070  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.070  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.070  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 22:31:04.071  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 22:31:04.071  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.073  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 22:31:04.073  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.073  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.073  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:31:04.073  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.074  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:04.074  5601  5649 I io.jxcore.node.ConnectionHelper: start: OK
11-04 22:31:04.074  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.074  4563  4626 D BtGatt.ScanManager: handling starting scan
,11-04 22:31:04.076  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.076  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.076  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.076  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:31:04.076  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 22:31:04.080  4563  4623 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-04 22:31:04.080  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.080  4563  4626 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 22:31:04.084  4563  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 22:31:04.085  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:04.085  4563  4626 D BtGatt.ScanManager: Starting BLE batch scan
11-04 22:31:04.085  4563  4626 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 22:31:04.093  4563  4623 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 22:31:04.093  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:31:04.097  4563  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 22:31:04.097  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:31:04.577  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 22:31:04.577  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:31:04.578  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 22:31:09.074  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:31:09.074  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:09.075  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 22:31:09.075  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:31:09.075  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-04 22:31:09.075  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:09.075  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 22:31:09.075  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,11-04 22:31:09.076  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 22:31:09.076  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 22:31:09.076  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.076  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:09.077  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.077  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 22:31:09.077  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:09.079  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:31:09.079  4563  4575 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 22:31:09.080  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 22:31:09.081  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 22:31:09.082  5601  5649 D BluetoothAdapter: STATE_ON
,11-04 22:31:09.083  4563  4776 D BtGatt.GattService: stopScan() - queue size =1
11-04 22:31:09.085  4563  4576 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 22:31:09.086  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 22:31:09.086  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.086  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 22:31:09.087  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.087  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.087  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.087  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:09.087  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 22:31:09.087  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.088  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.088  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.088  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 22:31:09.088  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 22:31:09.090  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:31:09.090  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.091  4563  4563 D BtGatt.ScanManager: awakened up at time 106498
,11-04 22:31:09.092   928  3317 I ActivityManager: Killing 5004:com.google.android.apps.messaging/u0a65 (adj 15): empty #17
11-04 22:31:09.093  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.093  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:31:09.093  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.093  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:09.094  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:31:09.094  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 22:31:09.094  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 22:31:09.094  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.094  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 22:31:09.094  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 22:31:09.095  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.095  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.095  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-04 22:31:09.095  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.098  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.098  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.098  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.098  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:31:09.098  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 22:31:09.154  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-04 22:31:09.154  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:09.154  4563  4623 D BtGatt.GattService: current time is 106562532690
11-04 22:31:09.155  4563  4623 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -84, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -86, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -75, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -85, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 22:31:09.155  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-04 22:31:09.156  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 22:31:09.156  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 22:31:09.156  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 22:31:09.157  4563  4623 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-04 22:31:09.162  4563  4623 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 22:31:09.162  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:09.162  4563  4626 D BtGatt.ScanManager: stopping BLe Batch
,11-04 22:31:09.167  4563  4623 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 22:31:09.167  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:31:09.167  4563  4626 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:31:09.172  4563  4623 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 22:31:09.172  4563  4623 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:31:09.600  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 22:31:09.600  5601  5601 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:09.600  5601  5601 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 22:31:14.095  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:31:14.096  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 22:31:14.096  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 22:31:14.096  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 22:31:14.096  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 22:31:14.096  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 22:31:14.097  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 22:31:14.097  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.097  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:14.097  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.097  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:14.097  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 22:31:14.100  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.103  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.104  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.104  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.104  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 22:31:14.104  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.104  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:14.105  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.109  5601  5649 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-04 22:31:14.110  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:31:14.111  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:14.111  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 22:31:14.111  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.111  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 22:31:14.111  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.111  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.112  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.112  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:14.113  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.115  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.116  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.116  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.116  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:14.116  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 22:31:14.116  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.116  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.118  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 22:31:14.119  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:14.119  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:14.119  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 22:31:14.119  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.119  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.120  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.120  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.120  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.120  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:14.120  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.123  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.123  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.123  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.123  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 22:31:14.123  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.124  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.124  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:14.126  5601  5649 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-04 22:31:14.126  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:31:14.127  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:14.127  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:14.127  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.127  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.127  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.127  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:14.127  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.127  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:14.128  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.130  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.130  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.130  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.131  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:14.131  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 22:31:14.131  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.131  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:14.133  5601  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-04 22:31:14.133  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:14.133  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:14.133  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:14.134  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.134  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 22:31:14.134  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.134  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.134  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.135  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:14.135  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.137  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.137  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.137  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.137  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:14.137  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.137  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.138  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:14.140  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 22:31:14.140  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 22:31:14.140  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 22:31:14.140  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 22:31:14.140  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 22:31:14.140  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 22:31:14.141  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 22:31:14.141  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-04 22:31:14.141  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 22:31:14.141  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:14.141  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:14.141  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:14.141  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.141  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.141  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.142  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.142  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.142  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:14.142  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.144  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.144  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.144  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.144  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 22:31:14.144  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.144  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.144  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:14.145  5601  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 22:31:14.145  5601  5649 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 22:31:14.146  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-04 22:31:14.150  5601  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 22:31:14.150  5601  5649 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-04 22:31:14.150  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 22:31:14.151  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-04 22:31:14.152  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 22:31:14.153  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 22:31:14.153  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 22:31:14.153  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 22:31:14.153  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 22:31:14.153  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 22:31:14.153  5601  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-04 22:31:14.153  5601  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 22:31:14.154  5601  5649 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-04 22:31:14.154  5601  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 22:31:14.154  5601  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-04 22:31:14.154  5601  5649 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-04 22:31:14.154  5601  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 22:31:14.154  5601  5649 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-04 22:31:14.154  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-04 22:31:14.157  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-04 22:31:14.158  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,11-04 22:31:14.158  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-04 22:31:14.159  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-04 22:31:14.159  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-04 22:31:14.159  5601  5649 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,11-04 22:31:14.159  5601  5649 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 22:31:14.160  5601  5649 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-04 22:31:14.160  5601  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-04 22:31:14.160  5601  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-04 22:31:14.161  5601  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-04 22:31:14.161  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:14.161  5601  5736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-04 22:31:14.161  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 22:31:14.161  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:14.161  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.161  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.161  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-04 22:31:14.163  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
,11-04 22:31:14.165  4776  4776 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30362]" dev="sockfs" ino=30362 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 22:31:14.163  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.163  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.163  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:14.163  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.164  5601  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-04 22:31:14.164  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.165  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.165  5601  5737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-04 22:31:14.165  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.165  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:14.165  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.165  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:14.165  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.165  5601  5736 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-04 22:31:14.165  5601  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 22:31:14.166  5601  5649 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-04 22:31:14.167  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:14.167  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:14.167  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:14.167  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.167  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.165  4776  4776 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30362]" dev="sockfs" ino=30362 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 22:31:14.167  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.167  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.167  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.167  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:14.168  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.169  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.169  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:14.169  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.169  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:14.169  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.169  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.170  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.170  5601  5649 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-04 22:31:14.171  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:14.171  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 22:31:14.171  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:14.171  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.171  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.171  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
,11-04 22:31:14.171  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.171  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.171  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:14.172  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.173  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.173  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.173  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.173  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:14.173  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.173  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:14.173  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.174  5601  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-04 22:31:14.176  5601  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-04 22:31:14.176  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 22:31:14.176  5601  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-04 22:31:14.176  5601  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 22:31:14.176  5601  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-04 22:31:14.176  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 22:31:14.176  5601  5649 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-04 22:31:14.176  5601  5649 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-04 22:31:14.176  5601  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 22:31:14.176  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 22:31:14.177  5601  5649 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 22:31:14.177  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:14.177  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:14.177  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:14.177  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.177  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.177  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.177  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.177  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.177  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:14.177  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.178  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.179  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.179  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:14.179  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:14.179  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:14.179  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.179  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:14.179  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:14.180  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:14.180  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:14.180  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:14.180  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:14.180  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:15.865   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-04 22:31:15.865   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 22:31:19.181  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:19.181  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.181  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:19.181  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:19.181  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
,11-04 22:31:19.182  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:19.182  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:19.182  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:19.182  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 22:31:19.183  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:19.183  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:19.183  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.183  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.183  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:19.184  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:19.187  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.187  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:19.187  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.187  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:19.188  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:19.188  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:19.188  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.192  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 22:31:19.193  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:31:19.193  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 22:31:19.199  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 22:31:19.202  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 22:31:19.202  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 22:31:19.202  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 22:31:19.203  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-04 22:31:19.203  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 22:31:19.203  5601  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-04 22:31:19.203  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 22:31:19.205  5601  5738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 22:31:19.207  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:19.207  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-04 22:31:19.207  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 22:31:19.207  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 22:31:19.208  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 22:31:19.209  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-04 22:31:19.209  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 22:31:19.209  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
,11-04 22:31:19.209  5601  5601 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-04 22:31:19.209  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.209  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 22:31:19.210  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 22:31:19.210  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 22:31:19.208  4575  4575 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[29588]" dev="sockfs" ino=29588 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 22:31:19.208  4575  4575 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[29588]" dev="sockfs" ino=29588 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 22:31:19.210  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.213  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.213  5601  5738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 22:31:19.213  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 22:31:19.213  5601  5738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 22:31:19.213  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.213  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.213  5601  5738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-04 22:31:19.214  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.214  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:31:19.214  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:19.214  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 22:31:19.214  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:19.214  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:31:19.214  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:31:19.214  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-04 22:31:19.214  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:19.214  5601  5601 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:19.215  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:19.215  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:19.215  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:19.215  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.215  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:19.216  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:19.218  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:19.218  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.218  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.218  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:19.219  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 22:31:19.219  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.219  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.221  5601  5649 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-04 22:31:19.221  5601  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 22:31:19.221  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-04 22:31:19.223  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 22:31:19.223  5601  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 22:31:19.223  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:19.223  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:19.223  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 22:31:19.223  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:19.223  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:19.223  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:19.224  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.224  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:19.224  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:19.224  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.227  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.227  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.228  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:31:19.228  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:19.228  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:19.228  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.230  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:19.235  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:31:19.235  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:19.236  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 22:31:19.236  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:19.236  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:19.236  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:19.236  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.236  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
,11-04 22:31:19.236  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:19.236  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.238  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.238  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.238  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.238  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 22:31:19.238  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:31:19.238  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.238  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.240  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:31:19.240  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:31:19.240  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-04 22:31:19.240  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:31:19.240  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:31:19.240  5601  5649 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca07be1 not in the list
11-04 22:31:19.240  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.240  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.240  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:19.241  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.243  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.243  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.243  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:31:19.243  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:31:19.243  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 22:31:19.243  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:19.243  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7197d06 not in the list
11-04 22:31:19.245  5601  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-04 22:31:19.245  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 22:31:19.246  5601  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 22:31:19.246  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-04 22:31:19.246  5601  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-04 22:31:19.246  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-04 22:31:19.250  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-04 22:31:19.250  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-04 22:31:19.250  5601  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-04 22:31:19.250  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 22:31:19.251  5601  5649 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-04 22:31:19.251  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 22:31:19.251  5601  5649 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-04 22:31:19.251  5601  5649 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-04 22:31:19.251  5601  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-04 22:31:19.251  5601  5649 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-04 22:31:19.252  5601  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-04 22:31:19.252  5601  5649 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-04 22:31:19.252  5601  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-04 22:31:19.252  5601  5649 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 22:31:19.254  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:31:19.254  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c8a8b7 added. We now have 3 listener(s)
11-04 22:31:19.254  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:31:19.256  5601  5649 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 22:31:19.257   928  3698 D WifiService: setWifiEnabled: true pid=5601, uid=10077
11-04 22:31:19.257   928  3698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 22:31:19.300  4563  4748 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-04 22:31:19.300  4563  4771 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-04 22:31:19.300  5601  5736 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-04 22:31:19.300  5601  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-04 22:31:19.301  5601  5736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,11-04 22:31:19.715  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 22:31:20.866   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:21.867   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:22.855   928  2846 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 22:31:22.868   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:23.869   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:24.263  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:31:24.263  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@561c824 added. We now have 4 listener(s)
,11-04 22:31:24.264  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:31:24.277  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:24.277  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@561c824 removed from the list
,11-04 22:31:24.278  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:24.280  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:31:24.280  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5755f8d added. We now have 4 listener(s)
,11-04 22:31:24.280  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:31:24.283  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 22:31:24.284  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5755f8d removed from the list
,11-04 22:31:24.284  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:24.285  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:31:24.285  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a24d542 added. We now have 4 listener(s)
,11-04 22:31:24.286  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:31:24.290   928  3698 D WifiService: setWifiEnabled: false pid=5601, uid=10077
11-04 22:31:24.290   928  3698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 22:31:24.298   928  2846 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-04 22:31:24.299   928  2846 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-04 22:31:24.299   928  2846 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 22:31:24.299   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 22:31:24.304  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 22:31:24.304  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 22:31:24.305  4563  4619 D BluetoothAdapterState: Current state: ON, message: 23
11-04 22:31:24.305  4563  4619 D BluetoothAdapterProperties: Setting state to 13
11-04 22:31:24.305  4563  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 22:31:24.306  4563  4619 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 22:31:24.306  4563  4619 I BluetoothAdapterState: Entering PendingCommandState
11-04 22:31:24.308  4563  4563 D BluetoothMapService: onReceive
11-04 22:31:24.308  4563  4563 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 22:31:24.309  4563  4563 D BluetoothMapService: STATE_TURNING_OFF
11-04 22:31:24.309  4563  4563 D BluetoothMapService: MAP Service closeService in
11-04 22:31:24.309  4563  4563 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 22:31:24.309  4563  4563 D ObexServerSockets0: shutdown(block = true)
11-04 22:31:24.310  4563  4563 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 22:31:24.310  4563  4563 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 22:31:24.311  4563  4771 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 22:31:24.311  4563  4786 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 22:31:24.311  4563  4785 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-04 22:31:24.316  4563  4563 I BtOppRfcommListener: stopping Accept Thread
11-04 22:31:24.317  4563  5192 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 22:31:24.317  4563  5192 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 22:31:24.322   506   922 D CommandListener: Clearing all IP addresses on wlan0
11-04 22:31:24.322   928  5270 D DhcpClient: Clearing IP address
11-04 22:31:24.327   506   922 D CommandListener: Setting iface cfg
11-04 22:31:24.329   928  5271 D DhcpClient: Receive thread stopped
11-04 22:31:24.336   928   941 I ActivityManager: Start proc 5742:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-04 22:31:24.339  4563  4623 D BluetoothAdapterProperties: Scan Mode:20
11-04 22:31:24.339  4563  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-04 22:31:24.342  3484  5329 V NativeCrypto: Read error: ssl=0x7f86021600: I/O error during system call, Connection timed out
,11-04 22:31:24.344  4563  4563 D HeadsetService: Received stop request...Stopping profile...
11-04 22:31:24.344  3484  5329 V NativeCrypto: SSL shutdown failed: ssl=0x7f86021600: I/O error during system call, Broken pipe
,11-04 22:31:24.346   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 22:31:24.347   928   939 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-04 22:31:24.347   928  5268 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-04 22:31:24.347  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 22:31:24.347  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 22:31:24.347  3017  3872 D BluetoothHeadset: Proxy object disconnected
11-04 22:31:24.348   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 22:31:24.348  4563  4563 D A2dpService: Received stop request...Stopping profile...
11-04 22:31:24.349  3670  3999 D BluetoothHeadset: Proxy object disconnected
11-04 22:31:24.349  4563  4779 D A2dpStateMachine: Exit Disconnected: -1
11-04 22:31:24.349   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 22:31:24.350  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:24.350  5601  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 22:31:24.350  5601  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 22:31:24.351   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-04 22:31:24.351   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-04 22:31:24.354   928  5268 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-04 22:31:24.355   532   532 E Parcel  : Reading a NULL string not supported here.
11-04 22:31:24.355   928   928 D BluetoothA2dp: Proxy object disconnected
11-04 22:31:24.357  3017  3017 D HeadsetProfile: Bluetooth service disconnected
11-04 22:31:24.357  3017  3017 D BluetoothA2dp: Proxy object disconnected
11-04 22:31:24.359  4563  4563 D HidService: Received stop request...Stopping profile...
11-04 22:31:24.359  4563  4563 D HidService: Stopping Bluetooth HidService
11-04 22:31:24.360  4563  4563 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:24.360  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.360  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.360  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:24.360  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:24.360  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 22:31:24.360  4563  4563 V BluetoothAdapterState: isTurningOff()=true
,11-04 22:31:24.360  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.360  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.361  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:24.361   928   928 D RttService: SCAN_AVAILABLE : 1
11-04 22:31:24.361   928  2966 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-04 22:31:24.362  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:24.362  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 22:31:24.363  4563  4563 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 22:31:24.364  4563  4563 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 22:31:24.364   928  2859 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-04 22:31:24.364  4563  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 22:31:24.364  4563  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:24.364  4563  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:24.364  4563  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:24.364  4563  4623 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 22:31:24.365  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:24.365  4563  4563 D HealthService: Received stop request...Stopping profile...
11-04 22:31:24.365  3617  3755 W QCNEJ   : |CORE| network lost: 100
11-04 22:31:24.366  3617  3755 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-04 22:31:24.368  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:24.370  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 22:31:24.375  4563  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 22:31:24.376  4563  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:24.376  4563  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:24.376  4563  4748 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 22:31:24.376  4563  4748 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 22:31:24.376  4563  4748 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 22:31:24.376  4563  4748 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 22:31:24.376  4563  4563 D PanService: Received stop request...Stopping profile...
11-04 22:31:24.378  4563  4563 D BluetoothMapService: Received stop request...Stopping profile...
11-04 22:31:24.378  4563  4563 D BluetoothMapService: stop()
11-04 22:31:24.380   928  2846 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-04 22:31:24.381  4563  4563 D BluetoothMapAppObserver: deinitObservers()
11-04 22:31:24.382  4563  4563 D BluetoothMapAppObserver: removeReceiver()
11-04 22:31:24.384  4563  4563 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:24.384  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.384  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.384  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:24.385  4563  4563 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 22:31:24.385  4563  4563 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 22:31:24.385  4563  4623 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 22:31:24.385  3017  3017 D BluetoothInputDevice: Proxy object disconnected
11-04 22:31:24.386  3017  3017 D HidProfile: Bluetooth service disconnected
11-04 22:31:24.386  4563  4563 D SapService: Received stop request...Stopping profile...
11-04 22:31:24.386  4563  4563 V SapService: stop()
11-04 22:31:24.387  3017  3017 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 22:31:24.387  3017  3017 D PanProfile: Bluetooth service disconnected
11-04 22:31:24.388  3017  3017 D BluetoothMap: Proxy object disconnected
11-04 22:31:24.388  3017  3017 D MapProfile: Bluetooth service disconnected
11-04 22:31:24.390   928  2846 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 22:31:24.393  4563  4563 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:24.393  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.393  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.393  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 22:31:24.393  4563  4563 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 22:31:24.393  4563  4563 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 22:31:24.393  4563  4623 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 22:31:24.394  4563  4563 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:24.394  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.394  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.394  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:24.394  4563  4563 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 22:31:24.394  4563  4563 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 22:31:24.394   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-04 22:31:24.395  4563  4563 D BluetoothMapService: MAP Service closeService in
11-04 22:31:24.395  4563  4563 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:24.395  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.395  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.395  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:24.396  4563  4563 D BluetoothMapService: cleanup()
11-04 22:31:24.396  4563  4563 D BluetoothMapService: MAP Service closeService in
11-04 22:31:24.396  4563  4563 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:24.396  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.396  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.396  4563  4563 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:24.396  4563  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 22:31:24.396  4563  4619 D BluetoothAdapterProperties: Setting state to 15
11-04 22:31:24.396  4563  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 22:31:24.397  3017  3028 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 22:31:24.398  4563  4619 I BluetoothAdapterState: Entering BleOnState
11-04 22:31:24.398  3017  3030 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:24.398  3670  3685 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:24.399  3017  3872 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 22:31:24.400   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:24.400  3017  3028 D BluetoothMap: onBluetoothStateChange: up=false
11-04 22:31:24.400   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 22:31:24.400   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:24.400   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:24.401  3017  3030 D BluetoothPan: onBluetoothStateChange on: false
11-04 22:31:24.401  3017  3872 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 22:31:24.402  4563  4619 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 22:31:24.402  4563  4619 D BluetoothAdapterProperties: Setting state to 16
11-04 22:31:24.402  4563  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 22:31:24.402  4563  4619 D BluetoothAdapterProperties: onBleDisable
11-04 22:31:24.403  4563  4619 I BluetoothAdapterState: Entering PendingCommandState
11-04 22:31:24.403  4563  4620 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 22:31:24.405  4563  4623 D BluetoothAdapterProperties: Scan Mode:20
11-04 22:31:24.405  4563  4748 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 22:31:24.405  4563  4748 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:24.406  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:24.406  5742  5742 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-04 22:31:24.407  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:24.414   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-04 22:31:24.414   506   922 D CommandListener: Clearing all IP addresses on wlan0
11-04 22:31:24.414   506   922 D TetherController: Setting IP forward enable = 0
11-04 22:31:24.415   928  2859 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-04 22:31:24.415   928  2859 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 22:31:24.416   928  2846 D DhcpClient: doQuit
11-04 22:31:24.416   928  2846 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 22:31:24.416   928  5270 D DhcpClient: onQuitting
11-04 22:31:24.417  3350  3350 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 22:31:24.418   928   945 D Tethering: MasterInitialState.processMessage what=3
11-04 22:31:24.426  3841  3841 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-04 22:31:24.427  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:24.427  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 22:31:24.428  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:24.428  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 22:31:24.430  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:24.434  5742  5742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 22:31:24.440  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 22:31:24.444   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c79a1e4:true
11-04 22:31:24.448  3350  3350 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-04 22:31:24.453  3350  3350 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-04 22:31:24.456   928  3317 I ActivityManager: Start proc 5774:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-04 22:31:24.470  5742  5742 D LocalBluetoothProfileManager: Adding local MAP profile
11-04 22:31:24.472   506   922 E Netd    : netlink response contains error (No such file or directory)
11-04 22:31:24.473  5742  5742 D BluetoothMap: Create BluetoothMap proxy object
11-04 22:31:24.473   506   922 D TetherController: Setting IP forward enable = 0
11-04 22:31:24.475   928  2859 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 22:31:24.481  5742  5742 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-04 22:31:24.490  5742  5742 D DockEventReceiver: finishStartingService: stopping service
,11-04 22:31:24.493   928  3317 I ActivityManager: Killing 5399:com.google.android.configupdater/u0a5 (adj 15): empty #17
,11-04 22:31:24.494  3350  3350 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 22:31:24.502  3350  3350 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 22:31:24.536  5774  5774 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-04 22:31:24.606  4390  4390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 22:31:24.606   928  2846 D wifi    : In wifi stop Hal
11-04 22:31:24.606   928  2846 D wifi    : halHandle = 0x7f84221080, mVM = 0x7fa084d140, mCls = 0x100a02
11-04 22:31:24.606   928  3348 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 22:31:24.606   928  3348 D WifiHAL : Got a signal to exit!!!
11-04 22:31:24.606   928  3348 I WifiHAL : Exit wifi_event_loop
11-04 22:31:24.607   928  2846 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 22:31:24.607   928  2846 E WifiHAL : Event processing terminated
,11-04 22:31:24.607   928  2846 D wifi    : In wifi cleaned up handler
11-04 22:31:24.607   928  2846 I WifiHAL : Internal cleanup completed
11-04 22:31:24.608  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:31:24.608  3852  4100 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 22:31:24.613  4563  4623 I bt_hci  : shut_down
,11-04 22:31:24.617  4563  4627 D bt_hwcfg: hw_epilog_process
,11-04 22:31:24.618  4563  4627 I bt_vendor: low_power_mode_cb
,11-04 22:31:24.620  4563  4627 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 22:31:24.620  4563  4627 I bt_vendor: epilog_cb
11-04 22:31:24.620  4563  4627 I bt_hci  : epilog_finished_callback
,11-04 22:31:24.623  4563  4623 I bt_hci_h4: hal_close
,11-04 22:31:24.623  4563  4623 I bt_userial_vendor: device fd = 54 close
,11-04 22:31:24.633   928  3348 D wifi    : set interface wlan0 flags (DOWN)
11-04 22:31:24.633   928  2846 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 22:31:24.717  5774  5774 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.717  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-04 22:31:24.718  5774  5774 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-04 22:31:24.718  5774  5774 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-04 22:31:24.718  5774  5774 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 22:31:24.718  5774  5774 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.k.d(PG:583)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 22:31:24.718  5774  5774 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
1,1-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 22:31:24.718  5774  5774 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 22:31:24.718  5774  5774 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:31:24.718  5774  5774 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 22:31:24.724  5742  5742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 22:31:24.730  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 22:31:24.732  4563  4620 D bt_stack_manager: event_shut_down_stack finished.
11-04 22:31:24.732  4563  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-04 22:31:24.734  4563  4563 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 22:31:24.735  4563  4619 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 22:31:24.735  4563  4563 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 22:31:24.735  4563  4563 D BtGatt.GattService: stop()
11-04 22:31:24.735  4563  4563 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 22:31:24.737  4563  4563 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:24.737  4563  4563 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:24.737  4563  4563 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:24.737  4563  4563 V BluetoothAdapterState: isBleTurningOff()=true
11-04 22:31:24.738  4563  4619 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 22:31:24.738  4563  4619 D BluetoothAdapterProperties: Setting state to 10
11-04 22:31:24.738  4563  4619 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 22:31:24.738  4563  4619 I BluetoothAdapterState: Entering OffState
11-04 22:31:24.739  3983  3983 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 22:31:24.739   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-04 22:31:24.747  4563  4563 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-04 22:31:24.747  4563  4563 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 22:31:24.747  4563  4563 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 22:31:24.749  4563  4620 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-04 22:31:24.751  3983  3983 D SystemUpdateService: onCreate
11-04 22:31:24.755  3983  3983 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-04 22:31:24.758  4563  4620 D bt_stack_manager: event_clean_up_stack finished.
,11-04 22:31:24.759  5742  5742 D DockEventReceiver: finishStartingService: stopping service
11-04 22:31:24.764  3983  3983 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-04 22:31:24.772  4563  4563 I art     : System.exit called, status: 0
11-04 22:31:24.772  4563  4563 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-04 22:31:24.785  3983  4184 I iu.UploadsManager: num queued entries: 0
11-04 22:31:24.785  3983  4184 I iu.UploadsManager: num updated entries: 0
11-04 22:31:24.792  3983  3983 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 22:31:24.793  3983  3983 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-04 22:31:24.794  3983  5809 I SystemUpdateService: active receiver: enabled
11-04 22:31:24.796  3983  4184 I iu.SyncManager: NEXT; no task
11-04 22:31:24.798  3983  5809 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 22:31:24.799  3983  5809 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 22:31:24.799  3983  5809 I SystemUpdateService: now status is 0 (complete)
11-04 22:31:24.799  3983  5809 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 22:31:24.799  3983  5809 I SystemUpdateService: file has been verified
11-04 22:31:24.800  3983  5809 I SystemUpdateService: OTA package size = 21989297
,11-04 22:31:24.813   928  3056 I ActivityManager: Process com.android.bluetooth (pid 4563) has died
,11-04 22:31:24.825   928  3318 I ActivityManager: Start proc 5811:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-04 22:31:24.836   928   945 D Tethering: InitialState.processMessage what=4
,11-04 22:31:24.842   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-04 22:31:24.842  3983  5809 I SystemUpdateService: showing system update notification
,11-04 22:31:24.857  5811  5811 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-04 22:31:24.859  5811  5811 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 22:31:24.866  5811  5811 D SprintDMHelper: simOperator: 
,11-04 22:31:24.866  5811  5811 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 22:31:24.870   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:24.878   928  3057 I ActivityManager: Start proc 5824:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-04 22:31:24.878   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-04 22:31:24.879   928  3057 I ActivityManager: Killing 5429:com.google.android.apps.gcs/u0a11 (adj 15): empty #17
,11-04 22:31:24.957  3983  3983 D SystemUpdateService: onDestroy
,11-04 22:31:24.959   928  3057 I ActivityManager: Killing 5334:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-04 22:31:25.004   928  3056 I ActivityManager: Start proc 5839:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-04 22:31:25.007   928  3704 I ActivityManager: Killing 5346:com.google.android.gms.unstable/u0a12 (adj 15): empty #17
,11-04 22:31:25.074  5839  5839 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-04 22:31:25.261   928  3056 I ActivityManager: Killing 3769:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-04 22:31:25.307   928  3524 I ActivityManager: Start proc 5851:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 22:31:25.342  5851  5851 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 22:31:25.351   928  3057 I ActivityManager: Killing 5495:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-04 22:31:25.361  5774  5797 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-04 22:31:25.371   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5285757:true
,11-04 22:31:25.870   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 22:31:29.353   928  3700 D WifiService: setWifiEnabled: true pid=5601, uid=10077
11-04 22:31:29.353   928  3700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 22:31:29.360   506   922 D SoftapController: Softap fwReload - Ok
,11-04 22:31:29.366   506   922 D CommandListener: Setting iface cfg
,11-04 22:31:29.366   506   922 D CommandListener: Trying to bring down wlan0
11-04 22:31:29.368   506   922 D CommandListener: Clearing all IP addresses on wlan0
,11-04 22:31:29.375   928  2846 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 22:31:29.933   928  2846 D wifi    : set interface wlan0 flags (UP)
11-04 22:31:29.935   928  2846 I WifiHAL : Initializing wifi
11-04 22:31:29.935   928  2846 I WifiHAL : Creating socket
11-04 22:31:29.936   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-04 22:31:29.937   928  2846 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 22:31:29.937   928  2846 D wifi    : Did set static halHandle = 0x7f84221080
11-04 22:31:29.937   928  2846 D wifi    : halHandle = 0x7f84221080, mVM = 0x7fa084d140, mCls = 0x1a02
11-04 22:31:29.938   928  2846 D wifi    : array field set
11-04 22:31:29.938   928  2846 I WifiNative-HAL: interface[0] = wlan0
11-04 22:31:29.939   928  5871 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547677671552
11-04 22:31:29.939   928  5871 D wifi    : waitForHalEvents called, vm = 0x7fa084d140, obj = 0x1a02, env = 0x7f88926d40
,11-04 22:31:29.942   928  2846 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 22:31:29.947  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:31:29.996  5872  5872 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 22:31:30.049  5872  5872 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 22:31:30.097  5872  5872 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 22:31:30.097  5872  5872 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 22:31:30.118   928  2846 D WifiConfigStore: Loading config and enabling all networks 
,11-04 22:31:30.119  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:30.119  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 22:31:30.119  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:30.119  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 22:31:30.137   928  2846 D WifiConfigStore: loaded 0 passpoint configs
,11-04 22:31:30.138   928  2846 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-04 22:31:30.139   928  2846 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-04 22:31:30.140   928  2846 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 22:31:30.140   928  2846 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 22:31:30.141   928  2846 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 22:31:30.142   928  2846 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-04 22:31:30.142   928  2846 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 22:31:30.142   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 22:31:30.142   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-04 22:31:30.142   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 22:31:30.142   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 22:31:30.142   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 22:31:30.146   928  2846 D WifiNative-HAL: Setting external_sim to 1
,11-04 22:31:30.146  4390  4390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 22:31:30.146   928  2846 D wifi    : setting dfs flag to true, 0x7f882ffa60
11-04 22:31:30.147   928  2846 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 22:31:30.147   928  2846 D wifi    : setting scan oui 0x7f882ffa60
11-04 22:31:30.147   928  2846 D WifiHAL : Sending mac address OUI
,11-04 22:31:30.151   928  2846 E native  : do suspend false
,11-04 22:31:30.158   928  2846 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 22:31:30.158   928   928 D RttService: SCAN_AVAILABLE : 3
11-04 22:31:30.158   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 22:31:30.158   928  2966 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 22:31:30.160   506   922 D CommandListener: Setting iface cfg
,11-04 22:31:30.163   928  2845 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-04 22:31:30.163   928  2845 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 22:31:30.172   928  2845 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 22:31:30.176   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=127584 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
11-04 22:31:30.176   928  2845 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 22:31:30.871   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:31.873   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:32.873   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:33.227  5872  5872 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 22:31:33.231  5872  5872 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 22:31:33.237  5872  5872 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 22:31:33.289   928  2846 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 22:31:33.290   928  2846 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-04 22:31:33.290   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 22:31:33.301   928  2846 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 22:31:33.336   928  2846 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 22:31:33.342  5872  5872 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 22:31:33.769  5872  5872 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 22:31:33.805  5872  5872 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 22:31:33.806  5872  5872 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 22:31:33.814   928  2846 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 22:31:33.815   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 22:31:33.815   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 22:31:33.833   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 22:31:33.847   506   922 D CommandListener: Setting iface cfg
,11-04 22:31:33.853   928  2846 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 22:31:33.859   928  5880 D DhcpClient: Receive thread started
,11-04 22:31:33.865   928  2859 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 22:31:33.865   928  2846 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 22:31:33.865   928  2859 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-04 22:31:33.874   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:33.947   928  2846 E native  : do suspend false
,11-04 22:31:33.963   928  5879 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 22:31:33.985   928  5880 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-04 22:31:33.985   928  5879 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-04 22:31:33.987   928  5879 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 22:31:34.008   928  5880 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 22:31:34.009   928  5879 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 22:31:34.012   506   922 D CommandListener: Setting iface cfg
,11-04 22:31:34.016   928  2846 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 22:31:34.021   928  5879 D DhcpClient: Scheduling renewal in 86399s
,11-04 22:31:34.031   928  2846 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 22:31:34.032   928  2846 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 22:31:34.036   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 22:31:34.038   928  2859 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 22:31:34.043   928  2846 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 22:31:34.080   928  2859 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 22:31:34.080   928  2859 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 22:31:34.082   928  2859 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-04 22:31:34.083   928  2859 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 22:31:34.085   928  2859 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 22:31:34.090   928  2859 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 22:31:34.095   928  2859 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-04 22:31:34.095   928  2859 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-04 22:31:34.095   928  2859 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 22:31:34.095   928  2846 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 22:31:34.095   928  2859 D ConnectivityService:    accepting network in place of null
11-04 22:31:34.095   928  2846 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 22:31:34.096   928  2859 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 22:31:34.109   928  5878 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131516, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 22:31:34.117   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 22:31:34.137   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 22:31:34.140   928  2859 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 22:31:34.140  3617  3755 W QCNEJ   : |CORE| network available: 101
11-04 22:31:34.140   928  2859 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 22:31:34.141  3617  3755 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-04 22:31:34.142   928   945 D Tethering: MasterInitialState.processMessage what=3
11-04 22:31:34.143  3617  3755 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 22:31:34.143   928  2859 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-04 22:31:34.143  3617  3755 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-04 22:31:34.147  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 22:31:34.147  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 22:31:34.147  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:34.147  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 22:31:34.159  3983  3983 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 22:31:34.167  3841  3841 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-04 22:31:34.167  3983  3983 D SystemUpdateService: onCreate
11-04 22:31:34.171  3983  3983 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 22:31:34.180  3983  5891 I SystemUpdateService: active receiver: enabled
,11-04 22:31:34.186   928  5877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 22:31:34.191  3983  5891 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 22:31:34.195  3983  3983 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 22:31:34.201  3983  4184 I iu.UploadsManager: num queued entries: 0
,11-04 22:31:34.203  3983  3983 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 22:31:34.204  3983  3983 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 22:31:34.206  5811  5811 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 22:31:34.214  5811  5811 D SprintDMHelper: simOperator: 
11-04 22:31:34.214  5811  5811 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 22:31:34.226  3983  5891 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 22:31:34.227  3983  5891 I SystemUpdateService: now status is 0 (complete)
11-04 22:31:34.227  3983  5891 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-04 22:31:34.227  3983  4184 I iu.UploadsManager: num updated entries: 0
,11-04 22:31:34.231   928  5877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 21:31:34 GMT], X-Android-Received-Millis=[1478295094231], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478295094210]}
11-04 22:31:34.232   928  2859 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 22:31:34.232   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-04 22:31:34.232   928  2859 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 22:31:34.233   928  2859 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 22:31:34.241  3983  5891 I SystemUpdateService: file has been verified
,11-04 22:31:34.241  3983  5891 I SystemUpdateService: OTA package size = 21989297
,11-04 22:31:34.247  3983  4184 I iu.SyncManager: NEXT; no task
,11-04 22:31:34.252  3983  5891 I SystemUpdateService: showing system update notification
,11-04 22:31:34.261   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 22:31:34.267  3983  3983 D SystemUpdateService: onDestroy
,11-04 22:31:34.272  3484  5901 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-04 22:31:34.303  3484  5899 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-04 22:31:34.306  3484  5899 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-04 22:31:34.336  3484  5899 W Uploader:  no longer exists, so no auth token.
,11-04 22:31:34.341  3484  5901 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 22:31:34.358   928  3057 D WifiService: setWifiEnabled: false pid=5601, uid=10077
11-04 22:31:34.359   928  3057 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 22:31:34.360   928  2846 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-04 22:31:34.360   928  2846 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 22:31:34.360   928  2846 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 22:31:34.360   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 22:31:34.367   928  5879 D DhcpClient: Clearing IP address
,11-04 22:31:34.367   506   922 D CommandListener: Clearing all IP addresses on wlan0
,11-04 22:31:34.369   506   922 D CommandListener: Setting iface cfg
11-04 22:31:34.370  3484  5905 V NativeCrypto: Read error: ssl=0x7f84eb7000: I/O error during system call, Connection timed out
11-04 22:31:34.370  3484  5905 V NativeCrypto: SSL shutdown failed: ssl=0x7f84eb7000: I/O error during system call, Broken pipe
11-04 22:31:34.372   928  5880 D DhcpClient: Receive thread stopped
,11-04 22:31:34.376   928   939 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-04 22:31:34.376   928  5877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-04 22:31:34.377   928  5877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
11-04 22:31:34.379   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-04 22:31:34.379   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-04 22:31:34.382   532   532 E Parcel  : Reading a NULL string not supported here.
11-04 22:31:34.384   928   928 D RttService: SCAN_AVAILABLE : 1
11-04 22:31:34.384   928  2966 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 22:31:34.386   928  2859 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-04 22:31:34.387  3617  3755 W QCNEJ   : |CORE| network lost: 101
11-04 22:31:34.388  3617  3755 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 22:31:34.389   928  5877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-04 22:31:34.391   928  2846 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 22:31:34.393   928  2846 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 22:31:34.407   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 22:31:34.427   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-04 22:31:34.427   506   922 D CommandListener: Clearing all IP addresses on wlan0
11-04 22:31:34.427   928  2859 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-04 22:31:34.428   928  2859 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 22:31:34.429   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-04 22:31:34.432   928  2846 D DhcpClient: doQuit
11-04 22:31:34.432   928  2846 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 22:31:34.432   928  5879 D DhcpClient: onQuitting
11-04 22:31:34.433  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:34.433  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 22:31:34.433  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 22:31:34.433  5872  5872 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 22:31:34.433  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 22:31:34.437  3841  3841 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 22:31:34.440  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:34.440  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 22:31:34.440  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:34.440  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 22:31:34.442  3983  3983 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 22:31:34.445  3983  3983 D SystemUpdateService: onCreate
,11-04 22:31:34.447  5872  5872 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 22:31:34.450  3983  3983 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 22:31:34.450  5872  5872 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 22:31:34.456  3983  5917 I SystemUpdateService: active receiver: enabled
,11-04 22:31:34.458  3983  3983 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 22:31:34.464  3983  4184 I iu.UploadsManager: num queued entries: 0
11-04 22:31:34.465  3983  4184 I iu.UploadsManager: num updated entries: 0
,11-04 22:31:34.468  3983  3983 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 22:31:34.469  3983  3983 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 22:31:34.471  5811  5811 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 22:31:34.475  5872  5872 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 22:31:34.477  5811  5811 D SprintDMHelper: simOperator: 
11-04 22:31:34.477  5811  5811 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 22:31:34.484  3983  5917 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 22:31:34.486  5872  5872 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 22:31:34.486   506   922 E Netd    : netlink response contains error (No such file or directory)
11-04 22:31:34.488   928  2859 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 22:31:34.488   928  2859 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 22:31:34.489  3983  4184 I iu.SyncManager: NEXT; no task
,11-04 22:31:34.492   928  2846 D wifi    : In wifi stop Hal
11-04 22:31:34.492   928  2846 D wifi    : halHandle = 0x7f84221080, mVM = 0x7fa084d140, mCls = 0x1a02
,11-04 22:31:34.492   928  5871 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 22:31:34.492   928  5871 D WifiHAL : Got a signal to exit!!!
11-04 22:31:34.492   928  5871 I WifiHAL : Exit wifi_event_loop
11-04 22:31:34.493  4390  4390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 22:31:34.493   928  2846 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 22:31:34.493   928  2846 E WifiHAL : Event processing terminated
,11-04 22:31:34.493   928  2846 D wifi    : In wifi cleaned up handler
11-04 22:31:34.493   928  2846 I WifiHAL : Internal cleanup completed
11-04 22:31:34.494  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:34.495  3852  4100 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 22:31:34.496  3983  5917 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-04 22:31:34.496  3983  5917 I SystemUpdateService: now status is 0 (complete)
11-04 22:31:34.496  3983  5917 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-04 22:31:34.496  3983  5917 I SystemUpdateService: file has been verified
11-04 22:31:34.497  3983  5917 I SystemUpdateService: OTA package size = 21989297
,11-04 22:31:34.512  3983  5917 I SystemUpdateService: showing system update notification
,11-04 22:31:34.514   928  5871 D wifi    : set interface wlan0 flags (DOWN)
,11-04 22:31:34.514   928  2846 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 22:31:34.519   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 22:31:34.520  3983  3983 D SystemUpdateService: onDestroy
,11-04 22:31:34.718   928   945 D Tethering: InitialState.processMessage what=4
,11-04 22:31:34.722   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 22:31:34.875   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:35.141   928  2859 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 22:31:35.876   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 22:31:39.359  3484  5899 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,11-04 22:31:39.392   928   945 I ActivityManager: Start proc 5924:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 22:31:39.467  5924  5924 D AdapterServiceConfig: Adding HeadsetService
11-04 22:31:39.467  5924  5924 D AdapterServiceConfig: Adding A2dpService
11-04 22:31:39.467  5924  5924 D AdapterServiceConfig: Adding HidService
11-04 22:31:39.468  5924  5924 D AdapterServiceConfig: Adding HealthService
11-04 22:31:39.468  5924  5924 D AdapterServiceConfig: Adding PanService
11-04 22:31:39.468  5924  5924 D AdapterServiceConfig: Adding GattService
11-04 22:31:39.468  5924  5924 D AdapterServiceConfig: Adding BluetoothMapService
11-04 22:31:39.468  5924  5924 D AdapterServiceConfig: Adding SapService
,11-04 22:31:39.477   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fff9459:true
,11-04 22:31:39.478  5924  5924 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 22:31:39.480  5924  5924 I bt_bluedroid: init
,11-04 22:31:39.480  5924  5936 I BluetoothAdapterState: Entering OffState
,11-04 22:31:39.482  5924  5937 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 22:31:39.482  5924  5937 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 22:31:39.482  5924  5937 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 22:31:39.482  5924  5937 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 22:31:39.483  5924  5924 I bt_bluedroid: get_profile_interface socket
,11-04 22:31:39.485  5924  5940 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 22:31:39.485  5924  5924 I bt_bluedroid: get_profile_interface sdp
11-04 22:31:39.486  5924  5940 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 22:31:39.490  5924  5935 I bt_bluedroid: config_hci_snoop_log
11-04 22:31:39.491   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 22:31:39.494  5924  5936 D BluetoothAdapterState: Current state: OFF, message: 0
11-04 22:31:39.494  5924  5936 D BluetoothAdapterProperties: Setting state to 14
,11-04 22:31:39.495  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 22:31:39.496  5924  5936 D BluetoothBondStateMachine: make
,11-04 22:31:39.498  5924  5941 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 22:31:39.500  5924  5936 I BluetoothAdapterState: Entering PendingCommandState
,11-04 22:31:39.501  5924  5924 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 22:31:39.503  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:39.504  5924  5924 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 22:31:39.504  5924  5924 D BtGatt.GattService: Received start request. Starting profile...
,11-04 22:31:39.504  5924  5924 D BtGatt.GattService: start()
11-04 22:31:39.504  5924  5924 I bt_bluedroid: get_profile_interface gatt
,11-04 22:31:39.506  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:39.506  5924  5924 D BtGatt.AdvertiseManager: advertise manager created
,11-04 22:31:39.510  5924  5924 V BluetoothAdapterState: isTurningOff()=false
,11-04 22:31:39.510  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:39.510  5924  5924 V BluetoothAdapterState: isBleTurningOn()=true
11-04 22:31:39.510  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:39.510  5924  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 22:31:39.511  5924  5936 I bt_bluedroid: bt_bluedroid
11-04 22:31:39.512  5924  5937 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 22:31:39.512  5924  5937 I bt_hci  : start_up
,11-04 22:31:39.516  5924  5937 I bt_vendor: alloc value 0xf3fbf871
11-04 22:31:39.517  5924  5937 I bt_vendor: init
11-04 22:31:39.517  5924  5937 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 22:31:39.517  5924  5937 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 22:31:39.629  5924  5937 D bt_hci  : start_up starting async portion
,11-04 22:31:39.629  5924  5944 I bt_hci  : event_finish_startup
11-04 22:31:39.629  5924  5944 I bt_hci_h4: hal_open
11-04 22:31:39.630  5924  5944 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 22:31:39.628  5945  5945 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 22:31:39.633  5924  5944 I bt_userial_vendor: device fd = 54 open
,11-04 22:31:39.647  5924  5944 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 22:31:39.650  5924  5944 D bt_hwcfg: Chipset BCM4358A3
,11-04 22:31:39.650  5924  5944 D bt_hwcfg: Target name = [BCM4358A3]
11-04 22:31:39.651  5924  5944 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 22:31:40.050  5924  5944 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 22:31:40.050  5924  5944 D bt_hwcfg: Settlement delay -- 100 ms
,11-04 22:31:40.051  5924  5944 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 22:31:40.185  5924  5944 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 22:31:40.185  5924  5944 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 22:31:40.187  5924  5944 I bt_hwcfg: vendor lib fwcfg completed
11-04 22:31:40.187  5924  5944 I bt_vendor: firmware callback
11-04 22:31:40.187  5924  5944 I bt_hci  : firmware_config_callback
,11-04 22:31:40.195  5924  5947 I bt_btu  : btu_task pending for preload complete event
,11-04 22:31:40.195  5924  5947 I bt_btu_task: Bluetooth chip preload is complete
,11-04 22:31:40.195  5924  5947 I bt_btu  : btu_task received preload complete event
,11-04 22:31:40.202  5924  5947 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 22:31:40.202  5924  5947 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_GAP
,11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 22:31:40.203  5924  5947 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 22:31:40.204  5924  5947 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 22:31:40.204  5924  5947 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 22:31:40.204  5924  5947 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 22:31:40.204  5924  5947 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 22:31:40.285  5924  5947 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f3d549
11-04 22:31:40.285  5924  5947 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f3d549 
,11-04 22:31:40.308  5924  5940 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 22:31:40.309  5924  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 22:31:40.310  5924  5940 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 22:31:40.312  5924  5940 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 22:31:40.314  5924  5940 D BluetoothAdapterProperties: Scan Mode:20
11-04 22:31:40.315  5924  5940 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 22:31:40.318  5924  5940 D bt_hci  : do_postload posting postload work item
11-04 22:31:40.318  5924  5944 I bt_hci  : event_postload
,11-04 22:31:40.319  5924  5944 I bt_vendor: sco_config_cb
11-04 22:31:40.319  5924  5944 I bt_hci  : sco_config_callback postload finished.
11-04 22:31:40.320  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:40.321  5924  5940 D bt_bte_conf: Device ID record 1 : primary
11-04 22:31:40.322  5924  5940 D bt_bte_conf:   vendorId            = 000f
11-04 22:31:40.322  5924  5940 D bt_bte_conf:   vendorIdSource      = 0001
11-04 22:31:40.322  5924  5940 D bt_bte_conf:   product             = 1200
11-04 22:31:40.322  5924  5940 D bt_bte_conf:   version             = 1436
11-04 22:31:40.322  5924  5940 D bt_bte_conf:   clientExecutableURL = 
11-04 22:31:40.322  5924  5940 D bt_bte_conf:   serviceDescription  = 
11-04 22:31:40.322  5924  5940 D bt_bte_conf:   documentationURL    = 
11-04 22:31:40.322  5924  5940 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 22:31:40.322  5924  5937 D bt_stack_manager: event_start_up_stack finished
11-04 22:31:40.323  5924  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-04 22:31:40.323  5924  5936 D BluetoothAdapterProperties: Setting state to 15
11-04 22:31:40.323  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 22:31:40.325  5924  5936 I BluetoothAdapterState: Entering BleOnState
,11-04 22:31:40.328  5924  5936 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-04 22:31:40.329  5924  5936 D BluetoothAdapterProperties: Setting state to 11
11-04 22:31:40.329  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 22:31:40.330  5924  5944 I bt_vendor: low_power_mode_cb
11-04 22:31:40.333  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:40.333  5924  5924 D HeadsetService: Received start request. Starting profile...
11-04 22:31:40.336  5924  5924 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 22:31:40.336  5924  5924 D HeadsetStateMachine: make
,11-04 22:31:40.340  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:31:40.347  5924  5924 D HeadsetStateMachine: max_hf_connections = 1
,11-04 22:31:40.347  5924  5924 I bt_bluedroid: get_profile_interface handsfree
11-04 22:31:40.347  5924  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 22:31:40.348  5924  5940 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 22:31:40.352  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:40.355  5924  5936 I BluetoothAdapterState: Entering PendingCommandState
11-04 22:31:40.355  5924  5924 D A2dpService: Received start request. Starting profile...
,11-04 22:31:40.356  5924  5924 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 22:31:40.356  5924  5924 I bt_bluedroid: get_profile_interface avrcp
,11-04 22:31:40.362  5924  5924 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 22:31:40.362  5924  5924 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 22:31:40.362  5924  5924 D A2dpStateMachine: make
,11-04 22:31:40.363  5924  5924 I bt_bluedroid: get_profile_interface a2dp
,11-04 22:31:40.365  5924  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 22:31:40.365  5924  5924 I BluetoothHidServiceJni: classInitNative: succeeds
11-04 22:31:40.365  5924  5955 D A2dpStateMachine: Enter Disconnected: -2
,11-04 22:31:40.366  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:40.368  5742  5742 D BluetoothInputDevice: Proxy object connected
,11-04 22:31:40.368  5924  5924 D HidService: Received start request. Starting profile...
11-04 22:31:40.368  5924  5924 I bt_bluedroid: get_profile_interface hidhost
11-04 22:31:40.369  5924  5924 D HidService: setHidService(): set to: null
11-04 22:31:40.369  5742  5742 D HidProfile: Bluetooth service connected
11-04 22:31:40.369  5924  5940 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1e56d
11-04 22:31:40.369  5924  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 22:31:40.369  5924  5924 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 22:31:40.370  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:40.371  5924  5924 D HealthService: Received start request. Starting profile...
,11-04 22:31:40.373  5924  5924 I bt_bluedroid: get_profile_interface health
,11-04 22:31:40.376  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:40.376  5924  5924 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:40.376  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:40.376  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:40.377  5924  5924 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-04 22:31:40.377  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 22:31:40.378  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:40.379  5924  5924 D PanService: Received start request. Starting profile...
11-04 22:31:40.380  5742  5742 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 22:31:40.380  5924  5924 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-04 22:31:40.380  5924  5924 I bt_bluedroid: get_profile_interface pan
,11-04 22:31:40.380  5924  5940 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 22:31:40.381  5742  5742 D PanProfile: Bluetooth service connected
,11-04 22:31:40.382  5924  5952 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,11-04 22:31:40.383  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:40.384  5742  5742 D BluetoothMap: Proxy object connected
,11-04 22:31:40.384  5742  5742 D MapProfile: Bluetooth service connected
11-04 22:31:40.384  5742  5742 D BluetoothMap: getConnectedDevices()
11-04 22:31:40.385  5924  5924 D BluetoothMapService: Received start request. Starting profile...
11-04 22:31:40.385  5924  5924 D BluetoothMapService: start()
11-04 22:31:40.388  5924  5924 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-04 22:31:40.389  5924  5924 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 22:31:40.389  5924  5924 D BluetoothMapAppObserver: createReceiver()
11-04 22:31:40.390  5924  5924 D BluetoothMapAppObserver: initObservers()
11-04 22:31:40.390  5924  5924 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 22:31:40.396  5924  5924 V SapService: SapBinder()
11-04 22:31:40.396  5924  5924 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d95cd53
,11-04 22:31:40.396  5924  5924 D SapService: Received start request. Starting profile...
11-04 22:31:40.396  5924  5924 V SapService: start()
11-04 22:31:40.397  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:40.397  5924  5924 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:40.397  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isTurningOn()=true
,11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:40.398  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:40.399  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:40.399  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:40.399  5924  5924 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:40.399  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:40.399  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 22:31:40.400  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:40.400  5924  5924 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:40.400  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:40.400  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 22:31:40.400  5924  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 22:31:40.400  5924  5936 D BluetoothAdapterProperties: ScanMode =  20
11-04 22:31:40.400  5924  5936 D BluetoothAdapterProperties: State =  11
11-04 22:31:40.402  5742  5742 D BluetoothMap: Bluetooth is Not enabled
11-04 22:31:40.403  5924  5940 D BluetoothAdapterProperties: Scan Mode:21
11-04 22:31:40.403  5924  5936 D BluetoothAdapterProperties: Setting state to 12
11-04 22:31:40.403  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-04 22:31:40.403  5924  5940 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 22:31:40.403  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 22:31:40.404  3017  3872 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 22:31:40.405  5924  5936 I BluetoothAdapterState: Entering OnState
11-04 22:31:40.407  5742  5759 D BluetoothMap: onBluetoothStateChange: up=true
11-04 22:31:40.407  3017  3028 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 22:31:40.407  3017  3017 D BluetoothA2dp: Proxy object connected
,11-04 22:31:40.408  5742  5757 D BluetoothPbap: onBluetoothStateChange: up=true
,11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:40.408  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 22:31:40.409  3670  3684 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 22:31:40.409  5742  5759 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 22:31:40.410  3017  3872 D BluetoothPbap: onBluetoothStateChange: up=true
,11-04 22:31:40.410  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 22:31:40.411   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 22:31:40.411  3017  3030 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 22:31:40.413  3017  3017 D BluetoothMap: Proxy object connected
11-04 22:31:40.413  5742  5757 D BluetoothPan: onBluetoothStateChange on: true
11-04 22:31:40.413  3017  3017 D MapProfile: Bluetooth service connected
11-04 22:31:40.413  3017  3017 D BluetoothMap: getConnectedDevices()
11-04 22:31:40.413   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 22:31:40.414   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 22:31:40.414   928   928 D BluetoothA2dp: Proxy object connected
11-04 22:31:40.414   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 22:31:40.414  3017  3872 D BluetoothPan: onBluetoothStateChange on: true
11-04 22:31:40.415  5924  5924 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 22:31:40.415  3017  3028 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 22:31:40.415  3017  3017 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 22:31:40.416  3017  3017 D PanProfile: Bluetooth service connected
11-04 22:31:40.416  5924  5924 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 22:31:40.417  5924  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 22:31:40.419  3017  3017 D BluetoothInputDevice: Proxy object connected
11-04 22:31:40.419  3017  3017 D HidProfile: Bluetooth service connected
11-04 22:31:40.419  5924  5924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 22:31:40.420  5924  5924 D ObexServerSockets: Succeed to create listening sockets 
11-04 22:31:40.420  5924  5924 D ObexServerSockets0: startAccept()
11-04 22:31:40.420  5924  5924 D ObexServerSockets0: prepareForNewConnect()
11-04 22:31:40.421   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 22:31:40.421  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 22:31:40.424  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:31:40.424  5924  5924 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 22:31:40.424  5924  5924 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 22:31:40.425  5924  5924 D BluetoothMapService: onReceive
11-04 22:31:40.425  5924  5961 D ObexServerSockets0: Accepting socket connection...
11-04 22:31:40.425  5924  5924 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-04 22:31:40.425  5924  5924 D BluetoothMapService: STATE_ON
11-04 22:31:40.425  5924  5962 D ObexServerSockets0: Accepting socket connection...
,11-04 22:31:40.425  5742  5742 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-04 22:31:40.427  5924  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 22:31:40.428  5924  5963 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 22:31:40.428  5924  5963 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 22:31:40.429  5742  5742 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-04 22:31:40.435  5742  5742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 22:31:40.437  5742  5742 D BluetoothA2dp: Proxy object connected
,11-04 22:31:40.442  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 22:31:40.444  5742  5742 D DockEventReceiver: finishStartingService: stopping service
,11-04 22:31:40.449  3017  3017 D BluetoothPbap: Proxy object connected
11-04 22:31:40.449  3017  3017 D PbapServerProfile: Bluetooth service connected
11-04 22:31:40.449  5742  5742 D BluetoothPbap: Proxy object connected
,11-04 22:31:40.450  5924  5924 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 22:31:40.450  5924  5924 D ObexServerSockets0: prepareForNewConnect()
11-04 22:31:40.450  5742  5742 D PbapServerProfile: Bluetooth service connected
,11-04 22:31:40.458  5924  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 22:31:40.474  5924  5971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 22:31:40.475  5924  5971 I BtOppRfcommListener: Accept thread started.
,11-04 22:31:40.509   928   928 D BluetoothHeadset: Proxy object connected
,11-04 22:31:40.509  3017  3028 D BluetoothHeadset: Proxy object connected
11-04 22:31:40.509  3017  3017 D HeadsetProfile: Bluetooth service connected
11-04 22:31:40.509   928   928 D BluetoothHeadset: Proxy object connected
11-04 22:31:40.509  3670  3685 D BluetoothHeadset: Proxy object connected
11-04 22:31:40.510   928   928 D BluetoothHeadset: Proxy object connected
11-04 22:31:40.510  3670  3999 D BluetoothHeadset: Proxy object connected
11-04 22:31:40.511   928   945 D BluetoothHeadset: Proxy object connected
,11-04 22:31:40.514   928   945 D BluetoothHeadset: Proxy object connected
,11-04 22:31:40.514   928   945 D BluetoothHeadset: Proxy object connected
,11-04 22:31:40.531  5742  5759 D BluetoothHeadset: Proxy object connected
,11-04 22:31:40.532  5742  5742 D HeadsetProfile: Bluetooth service connected
,11-04 22:31:41.787  3546  3728 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 22:31:41.787  3546  3728 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 22:31:41.815  3484  3484 I ConfigService: onCreate
,11-04 22:31:42.102   928  2859 D ConnectivityService: handlePromptUnvalidated 101
,11-04 22:31:44.378  5924  5936 D BluetoothAdapterState: Current state: ON, message: 23
11-04 22:31:44.378  5924  5936 D BluetoothAdapterProperties: Setting state to 13
11-04 22:31:44.378  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-04 22:31:44.380  5924  5936 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 22:31:44.381  5924  5936 I BluetoothAdapterState: Entering PendingCommandState
,11-04 22:31:44.386  5924  5924 D BluetoothMapService: onReceive
11-04 22:31:44.387  5924  5924 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 22:31:44.388  5924  5924 D BluetoothMapService: STATE_TURNING_OFF
11-04 22:31:44.388  5924  5924 D BluetoothMapService: MAP Service closeService in
11-04 22:31:44.389  5924  5924 D BluetoothMapMasInstance0: MAP Service shutdown
,11-04 22:31:44.389  5924  5924 D ObexServerSockets0: shutdown(block = true)
11-04 22:31:44.390  5924  5961 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 22:31:44.392  5924  5940 D BluetoothAdapterProperties: Scan Mode:20
11-04 22:31:44.394  5924  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-04 22:31:44.394  5924  5924 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-04 22:31:44.394  5924  5924 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-04 22:31:44.396  5924  5949 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 22:31:44.396  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:44.396  5601  5601 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 22:31:44.396  5924  5962 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 22:31:44.397  5601  5601 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 22:31:44.397  5601  5601 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 22:31:44.398  5924  5924 I BtOppRfcommListener: stopping Accept Thread
11-04 22:31:44.398  5924  5971 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 22:31:44.399  5924  5971 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 22:31:44.400  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:44.401  5924  5924 D HeadsetService: Received stop request...Stopping profile...
11-04 22:31:44.404   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 22:31:44.404  3017  3872 D BluetoothHeadset: Proxy object disconnected
,11-04 22:31:44.405   928   928 D BluetoothHeadset: Proxy object disconnected
,11-04 22:31:44.405  3670  3684 D BluetoothHeadset: Proxy object disconnected
11-04 22:31:44.406   928   928 D BluetoothHeadset: Proxy object disconnected
,11-04 22:31:44.406  5742  5757 D BluetoothHeadset: Proxy object disconnected
,11-04 22:31:44.407  5924  5924 D A2dpService: Received stop request...Stopping profile...
,11-04 22:31:44.407  5924  5955 D A2dpStateMachine: Exit Disconnected: -1
11-04 22:31:44.408   928   928 D BluetoothA2dp: Proxy object disconnected
11-04 22:31:44.409  5924  5924 D HidService: Received stop request...Stopping profile...
11-04 22:31:44.410  5924  5924 D HidService: Stopping Bluetooth HidService
11-04 22:31:44.411  5924  5924 D HealthService: Received stop request...Stopping profile...
11-04 22:31:44.411  5742  5742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 22:31:44.414  3017  3017 D HeadsetProfile: Bluetooth service disconnected
,11-04 22:31:44.414  3017  3017 D BluetoothA2dp: Proxy object disconnected
11-04 22:31:44.415  3017  3017 D BluetoothInputDevice: Proxy object disconnected
11-04 22:31:44.415  3017  3017 D HidProfile: Bluetooth service disconnected
11-04 22:31:44.415  5742  5742 D HeadsetProfile: Bluetooth service disconnected
11-04 22:31:44.417  5742  5742 D BluetoothA2dp: Proxy object disconnected
11-04 22:31:44.417  5742  5742 D BluetoothInputDevice: Proxy object disconnected
11-04 22:31:44.417  5742  5742 D HidProfile: Bluetooth service disconnected
11-04 22:31:44.418  5924  5924 D PanService: Received stop request...Stopping profile...
,11-04 22:31:44.419  3017  3017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-04 22:31:44.419  3017  3017 D PanProfile: Bluetooth service disconnected
11-04 22:31:44.420  5924  5924 V BluetoothAdapterState: isTurningOff()=true
,11-04 22:31:44.420  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.420  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.420  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:44.420  5924  5924 D BluetoothMapService: Received stop request...Stopping profile...
11-04 22:31:44.421  5924  5924 D BluetoothMapService: stop()
11-04 22:31:44.421  5924  5924 D BluetoothMapAppObserver: deinitObservers()
11-04 22:31:44.421  5924  5924 D BluetoothMapAppObserver: removeReceiver()
,11-04 22:31:44.422  5742  5742 D DockEventReceiver: finishStartingService: stopping service
11-04 22:31:44.422  3017  3017 D BluetoothMap: Proxy object disconnected
11-04 22:31:44.423  3017  3017 D MapProfile: Bluetooth service disconnected
,11-04 22:31:44.423  5742  5742 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 22:31:44.423  5742  5742 D PanProfile: Bluetooth service disconnected
11-04 22:31:44.424  5742  5742 D BluetoothMap: Proxy object disconnected
11-04 22:31:44.424  5742  5742 D MapProfile: Bluetooth service disconnected
,11-04 22:31:44.424  5924  5924 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 22:31:44.424  5924  5924 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 22:31:44.424  5924  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 22:31:44.425  5924  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 22:31:44.425  5924  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:44.425  5924  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:44.425  5924  5940 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 22:31:44.425  5924  5924 D SapService: Received stop request...Stopping profile...
11-04 22:31:44.425  5924  5924 V SapService: stop()
,11-04 22:31:44.427  5924  5924 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:44.427  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.427  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.427  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 22:31:44.428  5924  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-04 22:31:44.428  5924  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:44.428  5924  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:44.428  5924  5924 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:44.428  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.428  5924  5947 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-04 22:31:44.428  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.428  5924  5947 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 22:31:44.428  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:44.428  5924  5947 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 22:31:44.428  5924  5947 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 22:31:44.428  5924  5924 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 22:31:44.428  5924  5924 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 22:31:44.428  5924  5940 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 22:31:44.429  5924  5924 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:44.429  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.429  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.429  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:44.429  5924  5924 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 22:31:44.429  5924  5940 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 22:31:44.429  5924  5924 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-04 22:31:44.430  5924  5924 V BluetoothAdapterState: isTurningOff()=true
,11-04 22:31:44.431  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.431  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.431  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:44.431  5924  5924 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 22:31:44.431  5924  5924 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 22:31:44.432  5924  5924 D BluetoothMapService: MAP Service closeService in
11-04 22:31:44.432  5924  5924 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:44.432  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.432  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.432  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 22:31:44.432  5924  5924 D BluetoothMapService: cleanup()
11-04 22:31:44.432  5924  5924 D BluetoothMapService: MAP Service closeService in
11-04 22:31:44.432  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 22:31:44.432  5924  5924 V BluetoothAdapterState: isTurningOff()=true
11-04 22:31:44.432  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.433  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.433  5924  5924 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:44.433  5924  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 22:31:44.433  5924  5936 D BluetoothAdapterProperties: Setting state to 15
11-04 22:31:44.433  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 22:31:44.434  5924  5936 I BluetoothAdapterState: Entering BleOnState
11-04 22:31:44.435  3017  3017 D BluetoothPbap: Proxy object disconnected
11-04 22:31:44.435  3017  3017 D PbapServerProfile: Bluetooth service disconnected
11-04 22:31:44.435  5742  5742 D BluetoothPbap: Proxy object disconnected
11-04 22:31:44.435  5742  5742 D PbapServerProfile: Bluetooth service disconnected
11-04 22:31:44.435  3017  3028 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 22:31:44.436  5742  5759 D BluetoothMap: onBluetoothStateChange: up=false
11-04 22:31:44.439  3017  3872 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:44.439  5742  5757 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 22:31:44.440  5742  5759 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:44.440  3670  3685 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:44.440  5742  5757 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-04 22:31:44.441  3017  3028 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 22:31:44.441   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:44.441  3017  3030 D BluetoothMap: onBluetoothStateChange: up=false
11-04 22:31:44.442  5742  5759 D BluetoothPan: onBluetoothStateChange on: false
11-04 22:31:44.442   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 22:31:44.442   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:44.443  5742  5757 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 22:31:44.443   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 22:31:44.443  3017  3872 D BluetoothPan: onBluetoothStateChange on: false
11-04 22:31:44.444  3017  3028 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-04 22:31:44.444  5924  5936 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 22:31:44.444  5924  5936 D BluetoothAdapterProperties: Setting state to 16
11-04 22:31:44.444  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 22:31:44.445  5924  5936 D BluetoothAdapterProperties: onBleDisable
11-04 22:31:44.445  5924  5936 I BluetoothAdapterState: Entering PendingCommandState
11-04 22:31:44.445  5924  5937 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 22:31:44.446  5924  5940 D BluetoothAdapterProperties: Scan Mode:20
11-04 22:31:44.446  5924  5947 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 22:31:44.446  5924  5947 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 22:31:44.450  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:44.451  5742  5742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 22:31:44.451  5601  5601 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:31:44.458  5742  5742 D DockEventReceiver: finishStartingService: stopping service
11-04 22:31:44.459  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 22:31:44.657  5924  5940 I bt_hci  : shut_down
,11-04 22:31:44.667  5924  5944 D bt_hwcfg: hw_epilog_process
,11-04 22:31:44.667  5924  5944 I bt_vendor: low_power_mode_cb
,11-04 22:31:44.670  5924  5944 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 22:31:44.670  5924  5944 I bt_vendor: epilog_cb
,11-04 22:31:44.670  5924  5944 I bt_hci  : epilog_finished_callback
,11-04 22:31:44.676  5924  5940 I bt_hci_h4: hal_close
,11-04 22:31:44.676  5924  5940 I bt_userial_vendor: device fd = 54 close
,11-04 22:31:44.794  5924  5937 D bt_stack_manager: event_shut_down_stack finished.
,11-04 22:31:44.795  5924  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 22:31:44.799  5924  5936 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 22:31:44.799  5924  5924 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 22:31:44.800  5924  5924 D BtGatt.GattService: Received stop request...Stopping profile...
,11-04 22:31:44.800  5924  5924 D BtGatt.GattService: stop()
,11-04 22:31:44.800  5924  5924 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 22:31:44.804  5924  5924 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:44.804  5924  5924 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:44.804  5924  5924 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:44.805  5924  5924 V BluetoothAdapterState: isBleTurningOff()=true
11-04 22:31:44.805  5924  5936 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-04 22:31:44.806  5924  5936 D BluetoothAdapterProperties: Setting state to 10
11-04 22:31:44.806  5924  5936 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 22:31:44.807  5924  5936 I BluetoothAdapterState: Entering OffState
,11-04 22:31:44.808   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 22:31:44.823  5924  5924 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 22:31:44.823  5924  5924 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-04 22:31:44.823  5924  5924 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 22:31:44.826  5924  5937 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 22:31:44.832  5924  5924 I art     : System.exit called, status: 0
,11-04 22:31:44.833  5924  5924 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 22:31:44.862   928  3704 I ActivityManager: Process com.android.bluetooth (pid 5924) has died
,11-04 22:31:45.877   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:46.845  3484  3484 I ConfigService: onDestroy
,11-04 22:31:46.877   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:47.878   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:48.880   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:49.374  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:49.374  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 22:31:49.380  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:49.380  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a24d542 removed from the list
11-04 22:31:49.381  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:31:49.383  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:31:49.383  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e56789 added. We now have 4 listener(s)
11-04 22:31:49.383  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:31:49.388  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:49.388  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e56789 removed from the list
11-04 22:31:49.389  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:49.391  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:31:49.391  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42f038e added. We now have 4 listener(s)
,11-04 22:31:49.391  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:31:49.880   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:31:50.881   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 22:31:54.011   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 22:31:54.015   939   939 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[29491]" dev="sockfs" ino=29491 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:31:54.018   939   939 W Binder_2: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[29491]" dev="sockfs" ino=29491 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:31:54.028  3546  3546 I Keyboard.Facilitator: onFinishInput()
,11-04 22:31:54.041   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 22:31:54.041   928   948 I Adreno  : Build Date                       : 12/06/15
11-04 22:31:54.041   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 22:31:54.041   928   948 I Adreno  : Local Branch                     : mybranch17112971
11-04 22:31:54.041   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 22:31:54.041   928   948 I Adreno  : Remote Branch                    : NONE
11-04 22:31:54.041   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 22:31:54.077   382   407 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (138 us)
,11-04 22:31:54.401  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 22:31:54.439   928   945 I ActivityManager: Start proc 5983:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 22:31:54.506  5983  5983 D AdapterServiceConfig: Adding HeadsetService
,11-04 22:31:54.506  5983  5983 D AdapterServiceConfig: Adding A2dpService
11-04 22:31:54.506  5983  5983 D AdapterServiceConfig: Adding HidService
11-04 22:31:54.507  5983  5983 D AdapterServiceConfig: Adding HealthService
11-04 22:31:54.507  5983  5983 D AdapterServiceConfig: Adding PanService
11-04 22:31:54.507  5983  5983 D AdapterServiceConfig: Adding GattService
11-04 22:31:54.507  5983  5983 D AdapterServiceConfig: Adding BluetoothMapService
11-04 22:31:54.507  5983  5983 D AdapterServiceConfig: Adding SapService
,11-04 22:31:54.516   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60d4878:true
,11-04 22:31:54.517  5983  5983 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 22:31:54.519  5983  5983 I bt_bluedroid: init
,11-04 22:31:54.520  5983  5995 I BluetoothAdapterState: Entering OffState
,11-04 22:31:54.523  5983  5996 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 22:31:54.523  5983  5996 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 22:31:54.523  5983  5996 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 22:31:54.523  5983  5996 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 22:31:54.524  5983  5983 I bt_bluedroid: get_profile_interface socket
,11-04 22:31:54.526  5983  5999 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 22:31:54.526  5983  5983 I bt_bluedroid: get_profile_interface sdp
,11-04 22:31:54.527  5983  5999 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 22:31:54.530  5983  5994 I bt_bluedroid: config_hci_snoop_log
11-04 22:31:54.531   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 22:31:54.536  5983  5995 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 22:31:54.536  5983  5995 D BluetoothAdapterProperties: Setting state to 14
11-04 22:31:54.536  5983  5995 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-04 22:31:54.537  5983  5995 D BluetoothBondStateMachine: make
,11-04 22:31:54.539  5983  6000 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 22:31:54.542  5983  5995 I BluetoothAdapterState: Entering PendingCommandState
,11-04 22:31:54.543  5983  5983 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 22:31:54.546  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
,11-04 22:31:54.546  5983  5983 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 22:31:54.546  5983  5983 D BtGatt.GattService: Received start request. Starting profile...
11-04 22:31:54.547  5983  5983 D BtGatt.GattService: start()
11-04 22:31:54.547  5983  5983 I bt_bluedroid: get_profile_interface gatt
11-04 22:31:54.547  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
,11-04 22:31:54.547  5983  5983 D BtGatt.AdvertiseManager: advertise manager created
,11-04 22:31:54.552  5983  5983 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:54.553  5983  5983 V BluetoothAdapterState: isTurningOn()=false
11-04 22:31:54.553  5983  5983 V BluetoothAdapterState: isBleTurningOn()=true
11-04 22:31:54.553  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:54.553  5983  5995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 22:31:54.555  5983  5995 I bt_bluedroid: bt_bluedroid
11-04 22:31:54.555  5983  5996 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 22:31:54.555  5983  5996 I bt_hci  : start_up
,11-04 22:31:54.560  5983  5996 I bt_vendor: alloc value 0xf3fbf871
,11-04 22:31:54.561  5983  5996 I bt_vendor: init
11-04 22:31:54.561  5983  5996 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 22:31:54.561  5983  5996 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 22:31:54.669  5983  5996 D bt_hci  : start_up starting async portion
,11-04 22:31:54.669  5983  6003 I bt_hci  : event_finish_startup
11-04 22:31:54.669  5983  6003 I bt_hci_h4: hal_open
,11-04 22:31:54.669  5983  6003 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 22:31:54.668  6004  6004 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-04 22:31:54.672  5983  6003 I bt_userial_vendor: device fd = 54 open
,11-04 22:31:54.688  5983  6003 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 22:31:54.692  5983  6003 D bt_hwcfg: Chipset BCM4358A3
11-04 22:31:54.692  5983  6003 D bt_hwcfg: Target name = [BCM4358A3]
,11-04 22:31:54.693  5983  6003 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 22:31:54.756  5601  5601 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-04 22:31:54.757  5601  5601 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 22:31:54.791   928   948 I sensors : batch
,11-04 22:31:54.792   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-04 22:31:54.794  5601  5601 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8573b89 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@8edf7af, 16908290=android.view.AbsSavedState$1@8edf7af}, android:focusedViewId=100}]}]
11-04 22:31:54.794  5601  5601 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-04 22:31:54.795  5601  5601 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-04 22:31:54.795  5601  5601 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-04 22:31:54.796   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,11-04 22:31:54.796   928   948 I sensors : activate
11-04 22:31:54.797   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f9b143c00
,11-04 22:31:54.797   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-04 22:31:54.797   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-04 22:31:54.800   928  2633 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-04 22:31:54.801   928  2633 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 22:31:55.093   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 22:31:55.096   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-04 22:31:55.097   928  2985 D SurfaceControl: Excessive delay in setPowerMode(): 300ms
,11-04 22:31:55.106   928   948 I DreamManagerService: Entering dreamland.
11-04 22:31:55.106   928   948 I PowerManagerService: Dozing...
,11-04 22:31:55.107   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 22:31:55.140  5983  6003 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 22:31:55.141  5983  6003 D bt_hwcfg: Settlement delay -- 100 ms
11-04 22:31:55.141  5983  6003 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 22:31:55.141  3698  3698 W Binder_8: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33633]" dev="sockfs" ino=33633 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:31:55.141  3698  3698 W Binder_8: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33633]" dev="sockfs" ino=33633 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 22:31:55.143   928  3317 I sensors : batch
11-04 22:31:55.144   928  3317 I sensors : activate
,11-04 22:31:55.147   928  2633 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 22:31:55.148   928  2633 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-04 22:31:55.152   511   511 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 22:31:55.204  3670  4650 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 22:31:55.204  3670  4650 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 22:31:55.204  3670  4650 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 22:31:55.204   524  1197 D         : oem-qmi: Connection accepted
11-04 22:31:55.205   524  1197 D         : oem-qmi: Waiting to accept connection
,11-04 22:31:55.206   928   928 I sensors : activate
11-04 22:31:55.207   511  2897 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-04 22:31:55.209   928  2633 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-04 22:31:55.210  3670  4650 D         : oem_qmi_lib:output 0
11-04 22:31:55.210  3670  4650 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 22:31:55.229  3670  4650 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-04 22:31:55.229  3670  4650 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 22:31:55.229  3670  4650 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 22:31:55.229   524  1197 D         : oem-qmi: Connection accepted
11-04 22:31:55.229   524  1197 D         : oem-qmi: Waiting to accept connection
,11-04 22:31:55.235  3670  4650 D         : oem_qmi_lib:output 0
,11-04 22:31:55.235  3670  4650 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 22:31:55.274  5983  6003 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 22:31:55.274  5983  6003 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 22:31:55.275  5983  6003 I bt_hwcfg: vendor lib fwcfg completed
11-04 22:31:55.275  5983  6003 I bt_vendor: firmware callback
11-04 22:31:55.275  5983  6003 I bt_hci  : firmware_config_callback
,11-04 22:31:55.280  5983  6012 I bt_btu  : btu_task pending for preload complete event
11-04 22:31:55.280  5983  6012 I bt_btu_task: Bluetooth chip preload is complete
11-04 22:31:55.280  5983  6012 I bt_btu  : btu_task received preload complete event
,11-04 22:31:55.282  5983  6012 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 22:31:55.282  5983  6012 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_SDP
,11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 22:31:55.283  5983  6012 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 22:31:55.367  5983  6012 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f3d549
,11-04 22:31:55.367  5983  6012 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f3d549 
,11-04 22:31:55.375  5983  5999 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 22:31:55.377  5983  5999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 22:31:55.377  5983  5999 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 22:31:55.378  5983  5999 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 22:31:55.379  5983  5999 D BluetoothAdapterProperties: Scan Mode:20
,11-04 22:31:55.380  5983  5999 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 22:31:55.380  5983  5999 D bt_hci  : do_postload posting postload work item
11-04 22:31:55.380  5983  6003 I bt_hci  : event_postload
11-04 22:31:55.380  5983  6003 I bt_vendor: sco_config_cb
11-04 22:31:55.380  5983  6003 I bt_hci  : sco_config_callback postload finished.
,11-04 22:31:55.381  5983  5999 D bt_bte_conf: Device ID record 1 : primary
,11-04 22:31:55.381  5983  5999 D bt_bte_conf:   vendorId            = 000f
11-04 22:31:55.381  5983  5999 D bt_bte_conf:   vendorIdSource      = 0001
11-04 22:31:55.381  5983  5999 D bt_bte_conf:   product             = 1200
11-04 22:31:55.381  5983  5999 D bt_bte_conf:   version             = 1436
11-04 22:31:55.381  5983  5999 D bt_bte_conf:   clientExecutableURL = 
11-04 22:31:55.382  5983  5999 D bt_bte_conf:   serviceDescription  = 
,11-04 22:31:55.382  5983  5999 D bt_bte_conf:   documentationURL    = 
11-04 22:31:55.382  5983  5999 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 22:31:55.382  5983  5996 D bt_stack_manager: event_start_up_stack finished
,11-04 22:31:55.382  5983  5995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 22:31:55.382  5983  5995 D BluetoothAdapterProperties: Setting state to 15
11-04 22:31:55.383  5983  5995 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 22:31:55.383  5983  5995 I BluetoothAdapterState: Entering BleOnState
,11-04 22:31:55.386  5983  5995 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-04 22:31:55.386  5983  5995 D BluetoothAdapterProperties: Setting state to 11
11-04 22:31:55.387  5983  5995 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 22:31:55.388  5983  6003 I bt_vendor: low_power_mode_cb
11-04 22:31:55.390  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
,11-04 22:31:55.394  5983  5983 D HeadsetService: Received start request. Starting profile...
,11-04 22:31:55.396  5983  5983 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 22:31:55.396  5983  5983 D HeadsetStateMachine: make
,11-04 22:31:55.404  5983  5995 I BluetoothAdapterState: Entering PendingCommandState
,11-04 22:31:55.406  5983  5983 D HeadsetStateMachine: max_hf_connections = 1
11-04 22:31:55.406  5983  5983 I bt_bluedroid: get_profile_interface handsfree
11-04 22:31:55.407  5983  5999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 22:31:55.407  5983  5999 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 22:31:55.410  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
,11-04 22:31:55.410  5983  5983 D A2dpService: Received start request. Starting profile...
11-04 22:31:55.411  5983  5983 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 22:31:55.411  5983  5983 I bt_bluedroid: get_profile_interface avrcp
11-04 22:31:55.412  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 22:31:55.417  5983  5983 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 22:31:55.417  5983  5983 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 22:31:55.417  5983  5983 D A2dpStateMachine: make
,11-04 22:31:55.418  5983  5983 I bt_bluedroid: get_profile_interface a2dp
,11-04 22:31:55.419  5983  5999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-04 22:31:55.420  5983  6019 D A2dpStateMachine: Enter Disconnected: -2
11-04 22:31:55.420  5983  5983 I BluetoothHidServiceJni: classInitNative: succeeds
11-04 22:31:55.421  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
,11-04 22:31:55.422  5983  5983 D HidService: Received start request. Starting profile...
11-04 22:31:55.422  5983  5983 I bt_bluedroid: get_profile_interface hidhost
,11-04 22:31:55.422  5983  5999 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1e56d
11-04 22:31:55.422  5983  5983 D HidService: setHidService(): set to: null
11-04 22:31:55.422  5983  5999 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 22:31:55.423  5983  5983 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 22:31:55.423  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
11-04 22:31:55.424  5983  5983 D HealthService: Received start request. Starting profile...
,11-04 22:31:55.426  5983  5983 I bt_bluedroid: get_profile_interface health
,11-04 22:31:55.427  5983  5983 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-04 22:31:55.428  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
11-04 22:31:55.429  5983  5983 D PanService: Received start request. Starting profile...
11-04 22:31:55.429  5983  5983 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 22:31:55.429  5983  5983 I bt_bluedroid: get_profile_interface pan
11-04 22:31:55.429  5983  5999 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 22:31:55.431  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
,11-04 22:31:55.431  5983  5983 D BluetoothMapService: Received start request. Starting profile...
11-04 22:31:55.432  5983  5983 D BluetoothMapService: start()
11-04 22:31:55.434  5983  5983 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 22:31:55.435  5983  5983 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 22:31:55.435  5983  5983 D BluetoothMapAppObserver: createReceiver()
,11-04 22:31:55.436  5983  5983 D BluetoothMapAppObserver: initObservers()
11-04 22:31:55.437  5983  5983 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 22:31:55.443  5983  5983 V SapService: SapBinder()
,11-04 22:31:55.443  5983  5983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
11-04 22:31:55.443  5983  5983 D SapService: Received start request. Starting profile...
11-04 22:31:55.444  5983  5983 V SapService: start()
,11-04 22:31:55.445  5983  5983 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:55.446  5983  5983 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:55.446  5983  5983 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:55.446  5983  6017 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 22:31:55.446  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:55.446  5983  5983 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:55.446  5983  5983 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isTurningOff()=false
,11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:55.447  5983  5983 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:55.448  5983  5983 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:55.448  5983  5983 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:55.448  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:55.448  5983  5983 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:55.448  5983  5983 V BluetoothAdapterState: isTurningOn()=true
11-04 22:31:55.448  5983  5983 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:55.448  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
11-04 22:31:55.449  5983  5983 V BluetoothAdapterState: isTurningOff()=false
11-04 22:31:55.449  5983  5983 V BluetoothAdapterState: isTurningOn()=true
,11-04 22:31:55.449  5983  5983 V BluetoothAdapterState: isBleTurningOn()=false
11-04 22:31:55.449  5983  5983 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 22:31:55.449  5983  5995 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 22:31:55.449  5983  5995 D BluetoothAdapterProperties: ScanMode =  20
,11-04 22:31:55.449  5983  5995 D BluetoothAdapterProperties: State =  11
11-04 22:31:55.450  5983  5995 D BluetoothAdapterProperties: Setting state to 12
11-04 22:31:55.450  5983  5995 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 22:31:55.450  5983  5995 I BluetoothAdapterState: Entering OnState
11-04 22:31:55.450  3017  3030 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 22:31:55.451  5983  5999 D BluetoothAdapterProperties: Scan Mode:21
11-04 22:31:55.451  5983  5999 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-04 22:31:55.454  3017  3017 D BluetoothA2dp: Proxy object connected
,11-04 22:31:55.454  5742  5759 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 22:31:55.456  3017  3872 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 22:31:55.456  5742  5759 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 22:31:55.458  5742  5757 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 22:31:55.458  3670  3684 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 22:31:55.459  5742  5759 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 22:31:55.460  5742  5742 D BluetoothMap: Proxy object connected
11-04 22:31:55.460  3017  3028 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 22:31:55.460  5742  5742 D MapProfile: Bluetooth service connected
11-04 22:31:55.460  5742  5742 D BluetoothMap: getConnectedDevices()
,11-04 22:31:55.462   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 22:31:55.462  5983  5983 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 22:31:55.462  3017  3030 D BluetoothMap: onBluetoothStateChange: up=true
11-04 22:31:55.462  5983  5983 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 22:31:55.464  5983  5983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 22:31:55.464  3017  3017 D BluetoothMap: Proxy object connected
11-04 22:31:55.464  3017  3017 D MapProfile: Bluetooth service connected
11-04 22:31:55.464  3017  3017 D BluetoothMap: getConnectedDevices()
11-04 22:31:55.464  5742  5759 D BluetoothPan: onBluetoothStateChange on: true
,11-04 22:31:55.466   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 22:31:55.467   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 22:31:55.467   928   928 D BluetoothA2dp: Proxy object connected
11-04 22:31:55.467  5742  5757 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 22:31:55.467  5983  5983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 22:31:55.468  5983  5983 D ObexServerSockets: Succeed to create listening sockets 
11-04 22:31:55.469   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 22:31:55.469  5983  5983 D ObexServerSockets0: startAccept()
11-04 22:31:55.469  5983  5983 D ObexServerSockets0: prepareForNewConnect()
11-04 22:31:55.469  3017  3028 D BluetoothPan: onBluetoothStateChange on: true
11-04 22:31:55.470  3017  3030 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 22:31:55.470  5983  5983 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 22:31:55.470  5983  5983 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 22:31:55.471  5983  6026 D ObexServerSockets0: Accepting socket connection...
11-04 22:31:55.471  5742  5742 D BluetoothInputDevice: Proxy object connected
11-04 22:31:55.471  5983  6027 D ObexServerSockets0: Accepting socket connection...
11-04 22:31:55.471  5742  5742 D HidProfile: Bluetooth service connected
11-04 22:31:55.472  3017  3017 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 22:31:55.472  3017  3017 D PanProfile: Bluetooth service connected
11-04 22:31:55.473  3017  3017 D BluetoothInputDevice: Proxy object connected
11-04 22:31:55.473  3017  3017 D HidProfile: Bluetooth service connected
,11-04 22:31:55.474   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 22:31:55.474  5983  5983 D BluetoothMapService: onReceive
11-04 22:31:55.474  5983  5983 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-04 22:31:55.474  5983  5983 D BluetoothMapService: STATE_ON
11-04 22:31:55.476  5742  5742 D BluetoothA2dp: Proxy object connected
11-04 22:31:55.477  5983  6028 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 22:31:55.478  5742  5742 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 22:31:55.478  5742  5742 D PanProfile: Bluetooth service connected
,11-04 22:31:55.479  5983  6028 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 22:31:55.479  5983  6028 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 22:31:55.482  5742  5742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 22:31:55.487  3484  3484 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 22:31:55.487  5742  5742 D DockEventReceiver: finishStartingService: stopping service
,11-04 22:31:55.493  5742  5742 D BluetoothPbap: Proxy object connected
,11-04 22:31:55.493  5742  5742 D PbapServerProfile: Bluetooth service connected
,11-04 22:31:55.498  5983  5983 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 22:31:55.498  5983  5983 D ObexServerSockets0: prepareForNewConnect()
11-04 22:31:55.500  5983  6033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 22:31:55.501  3017  3017 D BluetoothPbap: Proxy object connected
11-04 22:31:55.501  3017  3017 D PbapServerProfile: Bluetooth service connected
,11-04 22:31:55.514  5983  6037 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 22:31:55.516  5983  6037 I BtOppRfcommListener: Accept thread started.
,11-04 22:31:55.558   928   928 D BluetoothHeadset: Proxy object connected
,11-04 22:31:55.558  5742  5759 D BluetoothHeadset: Proxy object connected
11-04 22:31:55.558  3017  3028 D BluetoothHeadset: Proxy object connected
11-04 22:31:55.558   928   928 D BluetoothHeadset: Proxy object connected
11-04 22:31:55.558  3017  3017 D HeadsetProfile: Bluetooth service connected
11-04 22:31:55.559  3670  3685 D BluetoothHeadset: Proxy object connected
,11-04 22:31:55.559  5742  5742 D HeadsetProfile: Bluetooth service connected
,11-04 22:31:55.559  3670  3999 D BluetoothHeadset: Proxy object connected
11-04 22:31:55.559   928   928 D BluetoothHeadset: Proxy object connected
11-04 22:31:55.559  5742  5757 D BluetoothHeadset: Proxy object connected
11-04 22:31:55.562  5742  5742 D HeadsetProfile: Bluetooth service connected
11-04 22:31:55.562   928   945 D BluetoothHeadset: Proxy object connected
,11-04 22:31:55.566   928   945 D BluetoothHeadset: Proxy object connected
,11-04 22:31:55.568   928   945 D BluetoothHeadset: Proxy object connected
,11-04 22:31:58.738  3852  4336 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:31:59.419  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 22:31:59.426  5601  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 22:31:59.427  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:31:59.427  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42f038e removed from the list
11-04 22:31:59.427  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:31:59.431  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:31:59.431  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f23f7bc added. We now have 4 listener(s)
11-04 22:31:59.431  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:31:59.433   928  3317 D WifiService: setWifiEnabled: false pid=5601, uid=10077
,11-04 22:31:59.433   928  3317 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 22:32:04.443  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 22:32:04.444   928  3057 D WifiService: setWifiEnabled: true pid=5601, uid=10077
11-04 22:32:04.444   928  3057 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 22:32:04.450   506   922 D SoftapController: Softap fwReload - Ok
,11-04 22:32:04.456   506   922 D CommandListener: Setting iface cfg
,11-04 22:32:04.456   506   922 D CommandListener: Trying to bring down wlan0
11-04 22:32:04.458   506   922 D CommandListener: Clearing all IP addresses on wlan0
,11-04 22:32:04.464   928  2846 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 22:32:05.135   928  2846 D wifi    : set interface wlan0 flags (UP)
,11-04 22:32:05.136   928  2846 I WifiHAL : Initializing wifi
11-04 22:32:05.137   928  2846 I WifiHAL : Creating socket
11-04 22:32:05.142   928  2846 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 22:32:05.142   928  2846 D wifi    : Did set static halHandle = 0x7f84221080
11-04 22:32:05.142   928  2846 D wifi    : halHandle = 0x7f84221080, mVM = 0x7fa084d140, mCls = 0x2015b6
11-04 22:32:05.143   928  2846 D wifi    : array field set
,11-04 22:32:05.143   928  2846 I WifiNative-HAL: interface[0] = wlan0
,11-04 22:32:05.145   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 22:32:05.146   928  6042 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547677671552
11-04 22:32:05.147   928  6042 D wifi    : waitForHalEvents called, vm = 0x7fa084d140, obj = 0x2015b6, env = 0x7f889271c0
11-04 22:32:05.149   928  2846 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 22:32:05.151   928  2846 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-04 22:32:05.206  6043  6043 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 22:32:05.280  6043  6043 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 22:32:05.367  6043  6043 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 22:32:05.367  6043  6043 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 22:32:05.883   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:06.166   928  2846 D WifiConfigStore: Loading config and enabling all networks 
,11-04 22:32:06.199   928  2846 D WifiConfigStore: loaded 0 passpoint configs
11-04 22:32:06.200   928  2846 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 22:32:06.201   928  2846 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 22:32:06.202   928  2846 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 22:32:06.202   928  2846 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 22:32:06.203   928  2846 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 22:32:06.204   928  2846 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 22:32:06.204   928  2846 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 22:32:06.204   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 22:32:06.204   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 22:32:06.204   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 22:32:06.204   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 22:32:06.204   928  2846 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 22:32:06.208   928  2846 D WifiNative-HAL: Setting external_sim to 1
,11-04 22:32:06.209  4390  4390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 22:32:06.209   928  2846 D wifi    : setting dfs flag to true, 0x7f893d4a20
,11-04 22:32:06.209   928  2846 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 22:32:06.210   928  2846 D wifi    : setting scan oui 0x7f893d4a20
11-04 22:32:06.210   928  2846 D WifiHAL : Sending mac address OUI
,11-04 22:32:06.214   928  2846 E native  : do suspend true
,11-04 22:32:06.223   928  2846 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 22:32:06.223   928   928 D RttService: SCAN_AVAILABLE : 3
11-04 22:32:06.223   506   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 22:32:06.223   928  2966 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-04 22:32:06.224   506   922 D CommandListener: Setting iface cfg
,11-04 22:32:06.235   928  2845 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
11-04 22:32:06.235   928  2845 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 22:32:06.243   928  2845 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 22:32:06.243   928  2845 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 22:32:06.249   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163657 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,11-04 22:32:06.884   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:07.886   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:08.887   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:09.364  6043  6043 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 22:32:09.390   928  2846 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 22:32:09.393   928  2846 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
11-04 22:32:09.395   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 22:32:09.409   928  2846 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 22:32:09.456  5601  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 22:32:09.460  5601  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 22:32:09.461   928  2846 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
11-04 22:32:09.461  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.461  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f23f7bc removed from the list
11-04 22:32:09.461  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 22:32:09.467  5601  5649 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-04 22:32:09.468  5601  5649 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-04 22:32:09.471  5601  5649 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8573b89 Bundle[{}]
,11-04 22:32:09.471  5601  5649 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 22:32:09.471  5601  5649 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-04 22:32:09.472  5601  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-04 22:32:09.472  5601  5649 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 22:32:09.473  5601  5649 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-04 22:32:09.473  5601  5649 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 22:32:09.480  5601  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-04 22:32:09.480  5601  5649 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-04 22:32:09.480  5601  5649 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-04 22:32:09.482  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 22:32:09.482  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f33f345 added. We now have 3 listener(s)
,11-04 22:32:09.484  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 22:32:09.484  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.484  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.484  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.484  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99bca9a added. We now have 4 listener(s)
11-04 22:32:09.484  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:32:09.485  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 22:32:09.487  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 22:32:09.487  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2c5fcb added. We now have 4 listener(s)
11-04 22:32:09.488  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:32:09.488  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.489  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.489  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.489  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@616d3a8 added. We now have 5 listener(s)
11-04 22:32:09.489  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.489  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:32:09.489  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:32:09.489  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:32:09.489  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 22:32:09.489  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.490  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:32:09.490  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f33f345 removed from the list
11-04 22:32:09.490  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.490  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99bca9a removed from the list
11-04 22:32:09.490  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:32:09.490  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.492  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.492  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.492  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.492  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.492  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:32:09.492  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.492  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99bca9a not in the list
11-04 22:32:09.492  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.494  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.494  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.494  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.494  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:32:09.494  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.494  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.494  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@616d3a8 removed from the list
11-04 22:32:09.494  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.494  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.495  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:32:09.495  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2c5fcb removed from the list
11-04 22:32:09.496  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 22:32:09.496  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8257ec1 added. We now have 3 listener(s)
,11-04 22:32:09.498  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 22:32:09.499  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.499  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 22:32:09.499  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:32:09.499  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edbf666 added. We now have 4 listener(s)
11-04 22:32:09.499  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.499  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 22:32:09.500  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 22:32:09.500  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f2da7 added. We now have 4 listener(s)
11-04 22:32:09.502  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:32:09.502  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.502  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.502  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 22:32:09.502  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d98254 added. We now have 5 listener(s)
11-04 22:32:09.502  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.502  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:32:09.502  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 22:32:09.502  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 22:32:09.502  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:32:09.502  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 22:32:09.504  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 22:32:09.507  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 22:32:09.507  5601  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 22:32:09.507  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 22:32:09.510  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.511  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 22:32:09.511  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 22:32:09.511  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 22:32:09.511  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 22:32:09.514  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.514  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 22:32:09.514  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 22:32:09.514  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 22:32:09.515  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 22:32:09.515  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.515  5601  5649 D BluetoothAdapter: STATE_ON
,11-04 22:32:09.518  5983  5994 D BtGatt.GattService: registerClient() - UUID=f5512147-79cd-43f7-b5a0-c76774645c2d
,11-04 22:32:09.519  5983  5999 D BtGatt.GattService: onClientRegistered() - UUID=f5512147-79cd-43f7-b5a0-c76774645c2d, clientIf=5
,11-04 22:32:09.519  5601  5611 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 22:32:09.520  5983  6025 D BtGatt.GattService: start scan with filters
,11-04 22:32:09.524  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 22:32:09.524  5983  6002 D BtGatt.ScanManager: handling starting scan
11-04 22:32:09.524  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.524  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-04 22:32:09.525  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.525  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 22:32:09.525  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 22:32:09.525  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 22:32:09.525  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 22:32:09.525  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 22:32:09.525  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.525  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.525  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 22:32:09.526  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-04 22:32:09.526  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.527  5983  6002 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@707d942
11-04 22:32:09.528  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.529  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:32:09.529  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.529  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.529  5601  5649 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 22:32:09.529  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.529  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 22:32:09.529  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 22:32:09.529  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.529  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:32:09.529  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.529  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 22:32:09.533  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 22:32:09.533  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 22:32:09.533  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.533  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.533  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 22:32:09.533  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 22:32:09.533  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:32:09.533  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 22:32:09.533  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.533  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.534  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.534  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 22:32:09.534  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.534  5983  5999 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 22:32:09.534  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.534  5983  6002 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 22:32:09.534  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:32:09.535  5983  5994 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-04 22:32:09.535  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 22:32:09.536  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:32:09.536  5983  5993 D BtGatt.GattService: stopScan() - queue size =1
11-04 22:32:09.537  5983  6029 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 22:32:09.537  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.538  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 22:32:09.538  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 22:32:09.540  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 22:32:09.540  5983  5999 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 22:32:09.540  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.540  5983  6002 D BtGatt.ScanManager: Starting BLE batch scan
11-04 22:32:09.540  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.540  5983  6002 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 22:32:09.541  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.541  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:32:09.541  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.542  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.542  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:32:09.542  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 22:32:09.542  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 22:32:09.542  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.542  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 22:32:09.542  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 22:32:09.542  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.542  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.542  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,11-04 22:32:09.542  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.544  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:32:09.544  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:32:09.544  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:32:09.544  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.544  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.544  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:32:09.544  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8257ec1 removed from the list
,11-04 22:32:09.545  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.545  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edbf666 removed from the list
11-04 22:32:09.545  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:32:09.545  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.546  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.546  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.546  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-04 22:32:09.546  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.546  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:32:09.546  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.546  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.546  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.546  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.546  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 22:32:09.546  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.546  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edbf666 not in the list
11-04 22:32:09.546  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.548  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.548  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.548  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.548  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:32:09.548  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.548  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.548  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d98254 removed from the list
11-04 22:32:09.548  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.548  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.548  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 22:32:09.548  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f2da7 removed from the list
11-04 22:32:09.549  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 22:32:09.549  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efa44f9 added. We now have 3 listener(s)
11-04 22:32:09.550  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:32:09.550  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.551  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 22:32:09.551  5983  5999 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 22:32:09.551  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.551  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.551  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3296c3e added. We now have 4 listener(s)
11-04 22:32:09.551  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 22:32:09.552  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 22:32:09.553  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 22:32:09.553  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d922a9f added. We now have 4 listener(s)
11-04 22:32:09.554  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 22:32:09.554  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.554  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.555  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.555  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@632c7ec added. We now have 5 listener(s)
11-04 22:32:09.555  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.555  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 22:32:09.556  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:32:09.556  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 22:32:09.556  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 22:32:09.556  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:32:09.556  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 22:32:09.556  5983  5999 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 22:32:09.556  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.558  5983  6002 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 22:32:09.558  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 22:32:09.562  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 22:32:09.562  5601  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 22:32:09.563  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 22:32:09.565  5983  5999 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 22:32:09.565  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.565  5983  5999 E BtGatt.ContextMap: Context not found for ID 5
,11-04 22:32:09.567  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.567  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 22:32:09.568  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 22:32:09.568  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 22:32:09.568  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 22:32:09.571  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.571  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 22:32:09.571  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 22:32:09.571  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 22:32:09.571  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 22:32:09.571  5983  5999 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 22:32:09.571  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.571  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.571  5983  6002 D BtGatt.ScanManager: stopping BLe Batch
,11-04 22:32:09.572  5601  5649 D BluetoothAdapter: STATE_ON
,11-04 22:32:09.573  5983  6029 D BtGatt.GattService: registerClient() - UUID=f5b903ff-3f09-40d9-84a4-f2b0fdcf97a9
11-04 22:32:09.574  5983  5999 D BtGatt.GattService: onClientRegistered() - UUID=f5b903ff-3f09-40d9-84a4-f2b0fdcf97a9, clientIf=5
,11-04 22:32:09.574  5601  5641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 22:32:09.574  5983  5993 D BtGatt.GattService: start scan with filters
,11-04 22:32:09.576  5983  5999 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 22:32:09.576  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.576  5983  6002 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 22:32:09.577  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 22:32:09.577  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.577  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 22:32:09.577  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.577  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 22:32:09.577  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 22:32:09.577  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.577  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 22:32:09.577  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-04 22:32:09.577  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.577  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.577  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 22:32:09.578  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 22:32:09.578  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.580  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.580  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:32:09.580  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.580  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.580  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.580  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:32:09.580  5601  5649 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 22:32:09.580  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:32:09.580  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:32:09.580  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:32:09.580  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.581  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.581  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:32:09.581  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 22:32:09.581  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:32:09.581  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efa44f9 removed from the list
11-04 22:32:09.581  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.581  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3296c3e removed from the list
11-04 22:32:09.581  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:32:09.581  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.581  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 22:32:09.581  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.581  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 22:32:09.581  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.581  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:32:09.581  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.581  5983  5999 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 22:32:09.581  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.582  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.582  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.582  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.582  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.582  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:32:09.582  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.582  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3296c3e not in the list
11-04 22:32:09.582  5983  6002 D BtGatt.ScanManager: handling starting scan
11-04 22:32:09.582  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.583  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.583  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.583  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-04 22:32:09.583  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:32:09.583  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 22:32:09.583  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 22:32:09.583  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 22:32:09.583  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.583  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.583  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.583  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 22:32:09.584  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.584  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:32:09.585  5983  5993 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 22:32:09.585  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 22:32:09.586  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:32:09.586  5983  5994 D BtGatt.GattService: stopScan() - queue size =1
11-04 22:32:09.587  5983  6024 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 22:32:09.588  5983  5999 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 22:32:09.588  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 22:32:09.588  5983  6002 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.588  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 22:32:09.588  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 22:32:09.589  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-04 22:32:09.592  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.593  5983  5999 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 22:32:09.593  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.593  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.593  5983  6002 D BtGatt.ScanManager: Starting BLE batch scan
11-04 22:32:09.593  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:32:09.593  5983  6002 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 22:32:09.593  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.593  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.593  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 22:32:09.593  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.594  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.594  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:32:09.594  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@632c7ec removed from the list
11-04 22:32:09.594  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:32:09.594  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.594  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.594  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 22:32:09.594  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 22:32:09.594  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.594  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d922a9f removed from the list
11-04 22:32:09.594  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 22:32:09.594  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 22:32:09.594  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.594  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.594  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 22:32:09.594  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.594  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 22:32:09.594  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6a9a31 added. We now have 3 listener(s)
11-04 22:32:09.595  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.595  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.595  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.595  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.595  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:32:09.595  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:32:09.596  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.596  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.596  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.596  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e44c516 added. We now have 4 listener(s)
11-04 22:32:09.596  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.598  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 22:32:09.599  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 22:32:09.599  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c58ce97 added. We now have 4 listener(s)
11-04 22:32:09.600  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:32:09.600  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.600  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.600  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.600  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c2884 added. We now have 5 listener(s)
11-04 22:32:09.600  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.600  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:32:09.600  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 22:32:09.600  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 22:32:09.600  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 22:32:09.601  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-04 22:32:09.602  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 22:32:09.602  5983  5999 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 22:32:09.602  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.605  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-04 22:32:09.605  5601  5649 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 22:32:09.605  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 22:32:09.606  5983  5999 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 22:32:09.607  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.608  5983  6002 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:32:09.609  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.609  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 22:32:09.610  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 22:32:09.610  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 22:32:09.610  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-04 22:32:09.612  5983  5999 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 22:32:09.612  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.613  5983  5999 E BtGatt.ContextMap: Context not found for ID 5
,11-04 22:32:09.614  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.614  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 22:32:09.614  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-04 22:32:09.614  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 22:32:09.614  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 22:32:09.614  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.615  5601  5649 D BluetoothAdapter: STATE_ON
,11-04 22:32:09.618  5983  6029 D BtGatt.GattService: registerClient() - UUID=7ed23068-b3ec-47a5-9699-7caf487a0818
,11-04 22:32:09.618  5983  5999 D BtGatt.GattService: onClientRegistered() - UUID=7ed23068-b3ec-47a5-9699-7caf487a0818, clientIf=5
,11-04 22:32:09.618  5983  5999 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 22:32:09.618  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.618  5983  6002 D BtGatt.ScanManager: stopping BLe Batch
11-04 22:32:09.618  5601  5641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 22:32:09.619  5983  6025 D BtGatt.GattService: start scan with filters
11-04 22:32:09.621  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 22:32:09.621  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.621  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 22:32:09.621  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.621  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 22:32:09.621  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 22:32:09.621  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.621  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 22:32:09.621  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 22:32:09.621  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.621  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.621  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 22:32:09.622  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 22:32:09.622  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.623  5983  5999 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 22:32:09.623  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.623  5983  6002 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 22:32:09.624  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.624  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:32:09.624  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.624  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.624  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 22:32:09.626  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 22:32:09.626  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:32:09.627  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:32:09.627  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.627  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.627  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:32:09.627  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.627  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:32:09.627  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6a9a31 removed from the list
11-04 22:32:09.627  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.627  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e44c516 removed from the list
11-04 22:32:09.627  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:32:09.627  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.627  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-04 22:32:09.627  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.627  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-04 22:32:09.627  5601  5649 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 22:32:09.627  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-04 22:32:09.627  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.627  5983  5999 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-04 22:32:09.627  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.628  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.628  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.628  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.628  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-04 22:32:09.628  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:32:09.628  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.628  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.628  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e44c516 not in the list
11-04 22:32:09.628  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.629  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-04 22:32:09.629  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.629  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 22:32:09.629  5983  6002 D BtGatt.ScanManager: handling starting scan
11-04 22:32:09.629  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 22:32:09.629  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 22:32:09.629  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 22:32:09.629  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.629  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.629  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.629  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 22:32:09.629  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.630  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:32:09.630  5983  6025 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-04 22:32:09.630  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-04 22:32:09.631  5601  5649 D BluetoothAdapter: STATE_ON
11-04 22:32:09.631  5983  6029 D BtGatt.GattService: stopScan() - queue size =1
11-04 22:32:09.632  5983  5993 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.633  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 22:32:09.633  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 22:32:09.634  5983  5999 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 22:32:09.634  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-04 22:32:09.634  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.634  5983  6002 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-04 22:32:09.634  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.635  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.635  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:32:09.635  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.635  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.636  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:32:09.636  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.636  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.636  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c2884 removed from the list
11-04 22:32:09.636  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.636  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.636  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:32:09.636  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c58ce97 removed from the list
11-04 22:32:09.637  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 22:32:09.637  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1795e69 added. We now have 3 listener(s)
11-04 22:32:09.638  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:32:09.638  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 22:32:09.638  5601  5601 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-04 22:32:09.638  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 22:32:09.638  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.638  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 22:32:09.638  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 22:32:09.638  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.638  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 22:32:09.638  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.638  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.638  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.639  5983  5999 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 22:32:09.639  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a760ee added. We now have 4 listener(s)
11-04 22:32:09.639  5601  5601 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
11-04 22:32:09.639  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.639  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.639  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.639  5983  6002 D BtGatt.ScanManager: Starting BLE batch scan
11-04 22:32:09.639  5983  6002 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 22:32:09.640  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 22:32:09.640  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 22:32:09.640  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e0f98f added. We now have 4 listener(s)
11-04 22:32:09.641  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.641  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.641  5601  5601 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.641  5601  5601 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 22:32:09.641  5601  5601 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 22:32:09.642  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 22:32:09.642  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 22:32:09.642  5601  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 22:32:09.642  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 22:32:09.642  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6e041c added. We now have 5 listener(s)
11-04 22:32:09.642  5601  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 22:32:09.642  5601  5649 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 22:32:09.642  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 22:32:09.642  5601  5649 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 22:32:09.642  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.642  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.642  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 22:32:09.643  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1795e69 removed from the list
11-04 22:32:09.643  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.643  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a760ee removed from the list
11-04 22:32:09.643  5601  5649 D io.jxcore.node.ConnectivityMonitor: stop
11-04 22:32:09.643  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.644  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.644  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.644  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.644  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.644  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-04 22:32:09.644  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.644  5601  5649 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a760ee not in the list
11-04 22:32:09.644  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.645  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 22:32:09.645  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.646  5601  5649 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 22:32:09.646  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-04 22:32:09.646  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-04 22:32:09.646  5601  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 22:32:09.646  5601  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6e041c removed from the list
11-04 22:32:09.646  5601  5649 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 22:32:09.646  5601  5649 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 22:32:09.646  5601  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 22:32:09.646  5601  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e0f98f removed from the list
11-04 22:32:09.647  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 22:32:09.647  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 22:32:09.647  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 22:32:09.647  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:32:09.647  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-04 22:32:09.647  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 22:32:09.648  5983  5999 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 22:32:09.648  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.653  5983  5999 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 22:32:09.653  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.654  5983  6002 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:32:09.658  5983  5999 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 22:32:09.658  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.658  5983  5999 E BtGatt.ContextMap: Context not found for ID 5
,11-04 22:32:09.664  5983  5999 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 22:32:09.664  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.664  5983  6002 D BtGatt.ScanManager: stopping BLe Batch
,11-04 22:32:09.668  5983  5999 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 22:32:09.669  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 22:32:09.669  5983  6002 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 22:32:09.673  5983  5999 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-04 22:32:09.673  5983  5999 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 22:32:09.789  6043  6043 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 22:32:09.813  6043  6043 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 22:32:09.813  6043  6043 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 22:32:09.826   928  2846 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 22:32:09.826   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 22:32:09.826   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 22:32:09.836   928  2846 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 22:32:09.844   506   922 D CommandListener: Setting iface cfg
,11-04 22:32:09.847   928  2846 D WifiStateMachine: Start Dhcp Watchdog 3
,11-04 22:32:09.850   928  2846 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 22:32:09.854   928  6048 D DhcpClient: Receive thread started
,11-04 22:32:09.887   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:09.935   928  2846 E native  : do suspend false
,11-04 22:32:09.946   928  6047 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 22:32:09.958   928  6048 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-04 22:32:09.959   928  6047 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-04 22:32:09.961   928  6047 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 22:32:09.988   928  6048 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 22:32:09.989   928  6047 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 22:32:09.992   506   922 D CommandListener: Setting iface cfg
11-04 22:32:09.997   928  2846 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 22:32:10.001   928  2846 E native  : do suspend true
,11-04 22:32:10.002   928  6047 D DhcpClient: Scheduling renewal in 86399s
,11-04 22:32:10.023   928  2846 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 22:32:10.024   928  2846 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 22:32:10.026   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-04 22:32:10.028   928  2859 D ConnectivityService: Adding iface wlan0 to network 102
,11-04 22:32:10.036   928  2846 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 22:32:10.047  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 22:32:10.093   928  2859 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 22:32:10.093   928  2859 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-04 22:32:10.096  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 22:32:10.096   928  2859 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-04 22:32:10.097   928  2859 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-04 22:32:10.099   928  2859 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-04 22:32:10.107   928  2859 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 22:32:10.112   928  2859 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-04 22:32:10.112   928  2859 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-04 22:32:10.112   928  2859 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-04 22:32:10.112   928  2846 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 22:32:10.112   928  2859 D ConnectivityService:    accepting network in place of null
11-04 22:32:10.112   928  2846 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 22:32:10.113   928  2859 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 22:32:10.130   928  6046 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167538, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 22:32:10.141  5601  5601 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 22:32:10.143   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 22:32:10.172   506   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 22:32:10.177   928  2859 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-04 22:32:10.177   928  2859 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 22:32:10.178  3617  3755 W QCNEJ   : |CORE| network available: 102
11-04 22:32:10.179   928  2859 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-04 22:32:10.180   928   945 D Tethering: MasterInitialState.processMessage what=3
11-04 22:32:10.181  3617  3755 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 22:32:10.182  3617  3755 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 22:32:10.183  3617  3755 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 22:32:10.196  3841  3841 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 22:32:10.198  3983  3983 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 22:32:10.201  3983  3983 D SystemUpdateService: onCreate
11-04 22:32:10.204   928  6045 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 22:32:10.210  3983  3983 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 22:32:10.224  3983  3983 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 22:32:10.230  3983  4184 I iu.UploadsManager: num queued entries: 0
,11-04 22:32:10.231  3983  4184 I iu.UploadsManager: num updated entries: 0
11-04 22:32:10.231  3983  4184 I iu.SyncManager: NEXT; no task
,11-04 22:32:10.232  3983  6059 I SystemUpdateService: active receiver: enabled
,11-04 22:32:10.234  3983  3983 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 22:32:10.236  3983  3983 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 22:32:10.237  5811  5811 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 22:32:10.241  5811  5811 D SprintDMHelper: simOperator: 
,11-04 22:32:10.241  5811  5811 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 22:32:10.255   928  6045 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 21:32:10 GMT], X-Android-Received-Millis=[1478295130254], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478295130227]}
,11-04 22:32:10.256   928  2859 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 22:32:10.256   928  2859 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-04 22:32:10.256   928  2859 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-04 22:32:10.257   928  2859 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 22:32:10.269  3983  6059 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 22:32:10.276  3983  6059 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 22:32:10.276  3983  6059 I SystemUpdateService: now status is 0 (complete)
11-04 22:32:10.276  3983  6059 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 22:32:10.276  3983  6059 I SystemUpdateService: file has been verified
11-04 22:32:10.276  3983  6059 I SystemUpdateService: OTA package size = 21989297
,11-04 22:32:10.281  3983  6059 I SystemUpdateService: showing system update notification
,11-04 22:32:10.288   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 22:32:10.291  3983  3983 D SystemUpdateService: onDestroy
,11-04 22:32:10.888   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-04 22:32:11.824  5601  6067 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 22:32:11.824  5601  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 22:32:12.622  5601  6067 W !!      : call onHalfStreamCopied
,11-04 22:32:12.622  5601  6067 I testCopyDataAndClose: closing input stream
,11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 22:32:13.397  5601  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 22:32:17.617  5601  6068 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:17.617  5601  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 22:32:18.121   928  2859 D ConnectivityService: handlePromptUnvalidated 102
,11-04 22:32:19.617  5601  5649 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-04 22:32:19.617  5601  5649 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 22:32:19.617  5601  5649 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-04 22:32:19.765  5601  6069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 22:32:19.765  5601  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 22:32:19.773  5601  6068 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-04 22:32:19.773  5601  6068 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:19.773  5601  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-04 22:32:21.393  5601  6069 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 22:32:21.393  5601  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 22:32:21.393  5601  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 22:32:21.393  5601  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 22:32:21.393  5601  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 22:32:21.394  5601  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 22:32:21.394  5601  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 22:32:21.394  5601  6069 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-04 22:32:21.394  5601  6069 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 22:32:21.394  5601  6069 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 22:32:21.394  5601  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 22:32:25.599  5601  6070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:25.599  5601  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 22:32:25.599  5601  6070 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:25.599  5601  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 22:32:25.599  5601  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 22:32:25.599  5601  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 22:32:25.600  5601  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 22:32:25.600  5601  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 22:32:25.600  5601  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 22:32:25.600  5601  6070 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 22:32:25.600  5601  6070 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-04 22:32:25.600  5601  6070 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:25.600  5601  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-04 22:32:25.602  5601  5649 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-04 22:32:25.605  5601  6071 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:25.605  5601  6071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 22:32:25.606  5601  6071 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-04 22:32:25.606  5601  6071 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:25.606  5601  6071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 22:32:25.606  5601  6071 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-04 22:32:25.607  5601  6071 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-04 22:32:25.607  5601  6071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 22:32:25.611  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-04 22:32:25.611  5601  5649 I jxcore-log: 
11-04 22:32:25.612  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-04 22:32:25.612  5601  5649 I jxcore-log: 
11-04 22:32:25.612  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-04 22:32:25.612  5601  5649 I jxcore-log: 
,11-04 22:32:25.613  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-04 22:32:25.613  5601  5649 I jxcore-log: 
11-04 22:32:25.613  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG UnitTest_app: 'Total duration:  91728'
11-04 22:32:25.613  5601  5649 I jxcore-log: 
,11-04 22:32:25.616  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 22:32:25.616  5601  5649 I jxcore-log: 
,11-04 22:32:25.621  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 22:32:25.621  5601  5649 I jxcore-log: 
,11-04 22:32:25.622  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 22:32:25.622  5601  5649 I jxcore-log: 
11-04 22:32:25.623  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 22:32:25.623  5601  5649 I jxcore-log: 
11-04 22:32:25.623  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 22:32:25.623  5601  5649 I jxcore-log: 
,11-04 22:32:25.623  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.623  5601  5649 I jxcore-log: 
11-04 22:32:25.624  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 22:32:25.624  5601  5649 I jxcore-log: 
,11-04 22:32:25.624  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.624  5601  5649 I jxcore-log: 
11-04 22:32:25.624  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 22:32:25.624  5601  5649 I jxcore-log: 
11-04 22:32:25.624  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 22:32:25.624  5601  5649 I jxcore-log: 
,11-04 22:32:25.625  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 22:32:25.625  5601  5649 I jxcore-log: 
11-04 22:32:25.625  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-04 22:32:25.625  5601  5649 I jxcore-log: 
11-04 22:32:25.625  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.625  5601  5649 I jxcore-log: 
,11-04 22:32:25.625  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 22:32:25.625  5601  5649 I jxcore-log: 
11-04 22:32:25.625  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.625  5601  5649 I jxcore-log: 
11-04 22:32:25.626  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 22:32:25.626  5601  5649 I jxcore-log: 
11-04 22:32:25.626  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.626  5601  5649 I jxcore-log: 
,11-04 22:32:25.626  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 22:32:25.626  5601  5649 I jxcore-log: 
11-04 22:32:25.626  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 22:32:25.626  5601  5649 I jxcore-log: 
11-04 22:32:25.627  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 22:32:25.627  5601  5649 I jxcore-log: 
,11-04 22:32:25.627  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 22:32:25.627  5601  5649 I jxcore-log: 
11-04 22:32:25.627  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 22:32:25.627  5601  5649 I jxcore-log: 
11-04 22:32:25.627  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 22:32:25.627  5601  5649 I jxcore-log: 
11-04 22:32:25.628  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 22:32:25.628  5601  5649 I jxcore-log: 
,11-04 22:32:25.628  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 22:32:25.628  5601  5649 I jxcore-log: 
11-04 22:32:25.629  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-04 22:32:25.629  5601  5649 I jxcore-log: 
11-04 22:32:25.630  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 22:32:25.630  5601  5649 I jxcore-log: 
11-04 22:32:25.630  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 22:32:25.630  5601  5649 I jxcore-log: 
11-04 22:32:25.630  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-04 22:32:25.630  5601  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-04 22:32:25.630  5601  5649 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 22:32:25.630  5601  5649 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-04 22:32:25.631  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 22:32:25.631  5601  5649 I jxcore-log: 
11-04 22:32:25.631  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.631  5601  5649 I jxcore-log: 
,11-04 22:32:25.631  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 22:32:25.631  5601  5649 I jxcore-log: 
11-04 22:32:25.631  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.631  5601  5649 I jxcore-log: 
11-04 22:32:25.631  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 22:32:25.631  5601  5649 I jxcore-log: 
11-04 22:32:25.632  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-04 22:32:25.632  5601  5649 I jxcore-log: 
,11-04 22:32:25.637  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 22:32:25.637  5601  5649 I jxcore-log: 
11-04 22:32:25.637  5601  5649 I jxcore-log: 2016-11-04 21:32:25 - WARN testUtils: 'myNameCallback not set!'
11-04 22:32:25.637  5601  5649 I jxcore-log: 
11-04 22:32:25.641  5601  5601 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-04 22:32:27.704  5601  5649 I jxcore-log: 2016-11-04 21:32:27 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-04 22:32:27.704  5601  5649 I jxcore-log: 
,11-04 22:32:27.706  5601  5649 I jxcore-log: 2016-11-04 21:32:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 22:32:27.706  5601  5649 I jxcore-log: 
,11-04 22:32:28.048  5601  5649 I jxcore-log: 2016-11-04 21:32:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 22:32:28.048  5601  5649 I jxcore-log: 
,11-04 22:32:28.060  5601  5649 I jxcore-log: 2016-11-04 21:32:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 22:32:28.060  5601  5649 I jxcore-log: 
,11-04 22:32:29.177  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 22:32:29.177  5601  5649 I jxcore-log: 
,11-04 22:32:29.364  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 22:32:29.364  5601  5649 I jxcore-log: 
,11-04 22:32:29.369  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 22:32:29.369  5601  5649 I jxcore-log: 
,11-04 22:32:29.374  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 22:32:29.374  5601  5649 I jxcore-log: 
,11-04 22:32:29.853  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 22:32:29.853  5601  5649 I jxcore-log: 
,11-04 22:32:29.897  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 22:32:29.897  5601  5649 I jxcore-log: 
,11-04 22:32:29.911  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 22:32:29.911  5601  5649 I jxcore-log: 
,11-04 22:32:29.915  5601  5649 I jxcore-log: 2016-11-04 21:32:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 22:32:29.915  5601  5649 I jxcore-log: 
,11-04 22:32:30.182  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 22:32:30.182  5601  5649 I jxcore-log: 
,11-04 22:32:30.307  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 22:32:30.307  5601  5649 I jxcore-log: 
,11-04 22:32:30.680  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 22:32:30.680  5601  5649 I jxcore-log: 
,11-04 22:32:30.688  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 22:32:30.688  5601  5649 I jxcore-log: 
,11-04 22:32:30.692  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 22:32:30.692  5601  5649 I jxcore-log: 
,11-04 22:32:30.697  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 22:32:30.697  5601  5649 I jxcore-log: 
,11-04 22:32:30.702  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 22:32:30.702  5601  5649 I jxcore-log: 
,11-04 22:32:30.729  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 22:32:30.729  5601  5649 I jxcore-log: 
,11-04 22:32:30.765  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 22:32:30.765  5601  5649 I jxcore-log: 
,11-04 22:32:30.772  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 22:32:30.772  5601  5649 I jxcore-log: 
,11-04 22:32:30.779  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 22:32:30.779  5601  5649 I jxcore-log: 
,11-04 22:32:30.794  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 22:32:30.794  5601  5649 I jxcore-log: 
,11-04 22:32:30.798  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 22:32:30.798  5601  5649 I jxcore-log: 
,11-04 22:32:30.804  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 22:32:30.804  5601  5649 I jxcore-log: 
,11-04 22:32:30.809  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 22:32:30.809  5601  5649 I jxcore-log: 
,11-04 22:32:30.822  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 22:32:30.822  5601  5649 I jxcore-log: 
,11-04 22:32:30.839  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 22:32:30.839  5601  5649 I jxcore-log: 
,11-04 22:32:30.853  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 22:32:30.853  5601  5649 I jxcore-log: 
,11-04 22:32:30.864  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 22:32:30.864  5601  5649 I jxcore-log: 
,11-04 22:32:30.887  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 22:32:30.887  5601  5649 I jxcore-log: 
,11-04 22:32:30.889   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:30.897  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 22:32:30.897  5601  5649 I jxcore-log: 
,11-04 22:32:30.911  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 22:32:30.911  5601  5649 I jxcore-log: 
,11-04 22:32:30.921  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 22:32:30.921  5601  5649 I jxcore-log: 
,11-04 22:32:30.928  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 22:32:30.928  5601  5649 I jxcore-log: 
,11-04 22:32:30.950  5601  5649 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 22:32:30.951  5601  5649 I jxcore-log: 2016-11-04 21:32:30 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 22:32:30.951  5601  5649 I jxcore-log: 
,11-04 22:32:31.040  5601  5649 I jxcore-log: 2016-11-04 21:32:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:31.040  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:31.040  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:31.040  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:31.040  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:31.040  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:31.040  5601  5649 I jxcore-log: 
,11-04 22:32:31.224  5601  5649 I jxcore-log: 2016-11-04 21:32:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:31.224  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:31.224  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:31.224  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:31.224  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:31.224  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:31.224  5601  5649 I jxcore-log: 
,11-04 22:32:31.227  5601  5649 I jxcore-log: 2016-11-04 21:32:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:31.227  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:31.227  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:31.227  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:31.227  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:31.227  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:31.227  5601  5649 I jxcore-log: 
,11-04 22:32:31.731  5601  5649 I jxcore-log: 2016-11-04 21:32:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:31.731  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:31.731  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:31.731  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:31.731  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:31.731  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:31.731  5601  5649 I jxcore-log: 
11-04 22:32:31.734  5601  5649 I jxcore-log: 2016-11-04 21:32:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:31.734  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:31.734  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:31.734  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:31.734  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:31.734  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:31.734  5601  5649 I jxcore-log: 
,11-04 22:32:31.891   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:32.767  5601  5649 I jxcore-log: 2016-11-04 21:32:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:32.767  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:32.767  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:32.767  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:32.767  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:32.767  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:32.767  5601  5649 I jxcore-log: 
,11-04 22:32:32.769  5601  5649 I jxcore-log: 2016-11-04 21:32:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:32.769  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:32.769  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:32.769  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:32.769  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:32.769  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:32.769  5601  5649 I jxcore-log: 
,11-04 22:32:32.892   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:33.803  5601  5649 I jxcore-log: 2016-11-04 21:32:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:33.803  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:33.803  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:33.803  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:33.803  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:33.803  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:33.803  5601  5649 I jxcore-log: 
,11-04 22:32:33.809  5601  5649 I jxcore-log: 2016-11-04 21:32:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:33.809  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:33.809  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:33.809  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:33.809  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:33.809  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:33.809  5601  5649 I jxcore-log: 
,11-04 22:32:33.893   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:34.847  5601  5649 I jxcore-log: 2016-11-04 21:32:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:34.847  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:34.847  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:34.847  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:34.847  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:34.847  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:34.847  5601  5649 I jxcore-log: 
,11-04 22:32:34.851  5601  5649 I jxcore-log: 2016-11-04 21:32:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:34.851  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:34.851  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:34.851  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:34.851  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:34.851  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:34.851  5601  5649 I jxcore-log: 
,11-04 22:32:34.894   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 22:32:35.882  5601  5649 I jxcore-log: 2016-11-04 21:32:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:35.882  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:35.882  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:35.882  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:35.882  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:35.882  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:35.882  5601  5649 I jxcore-log: 
,11-04 22:32:35.886  5601  5649 I jxcore-log: 2016-11-04 21:32:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:35.886  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:35.886  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:35.886  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:35.886  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:35.886  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:35.886  5601  5649 I jxcore-log: 
,11-04 22:32:35.894   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 22:32:36.919  5601  5649 I jxcore-log: 2016-11-04 21:32:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:36.919  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:36.919  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:36.919  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:36.919  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:36.919  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:36.919  5601  5649 I jxcore-log: 
,11-04 22:32:36.922  5601  5649 I jxcore-log: 2016-11-04 21:32:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:36.922  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:36.922  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:36.922  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:36.922  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:36.922  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:36.922  5601  5649 I jxcore-log: 
,11-04 22:32:37.959  5601  5649 I jxcore-log: 2016-11-04 21:32:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:37.959  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:37.959  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:37.959  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:37.959  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:37.959  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:37.959  5601  5649 I jxcore-log: 
,11-04 22:32:37.962  5601  5649 I jxcore-log: 2016-11-04 21:32:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:37.962  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:37.962  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:37.962  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:37.962  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:37.962  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:37.962  5601  5649 I jxcore-log: 
,11-04 22:32:39.092  5601  5649 I jxcore-log: 2016-11-04 21:32:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:39.092  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:39.092  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:39.092  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:39.092  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:39.092  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:39.092  5601  5649 I jxcore-log: 
,11-04 22:32:39.097  5601  5649 I jxcore-log: 2016-11-04 21:32:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:39.097  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:39.097  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:39.097  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:39.097  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:39.097  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:39.097  5601  5649 I jxcore-log: 
,11-04 22:32:40.168  5601  5649 I jxcore-log: 2016-11-04 21:32:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:40.168  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:40.168  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:40.168  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:40.168  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:40.168  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:40.168  5601  5649 I jxcore-log: 
,11-04 22:32:40.172  5601  5649 I jxcore-log: 2016-11-04 21:32:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:40.172  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:40.172  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:40.172  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:40.172  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:40.172  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:40.172  5601  5649 I jxcore-log: 
,11-04 22:32:41.208  5601  5649 I jxcore-log: 2016-11-04 21:32:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:41.208  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:41.208  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:41.208  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:41.208  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:41.208  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:41.208  5601  5649 I jxcore-log: 
,11-04 22:32:41.214  5601  5649 I jxcore-log: 2016-11-04 21:32:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:41.214  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:41.214  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:41.214  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:41.214  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:41.214  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:41.214  5601  5649 I jxcore-log: 
,11-04 22:32:42.242  5601  5649 I jxcore-log: 2016-11-04 21:32:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:42.242  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:42.242  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:42.242  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:42.242  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:42.242  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:42.242  5601  5649 I jxcore-log: 
,11-04 22:32:42.247  5601  5649 I jxcore-log: 2016-11-04 21:32:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:42.247  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:42.247  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:42.247  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:42.247  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:42.247  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:42.247  5601  5649 I jxcore-log: 
,11-04 22:32:43.273  5601  5649 I jxcore-log: 2016-11-04 21:32:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:43.273  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:43.273  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:43.273  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:43.273  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:43.273  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:43.273  5601  5649 I jxcore-log: 
,11-04 22:32:43.276  5601  5649 I jxcore-log: 2016-11-04 21:32:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:43.276  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:43.276  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:43.276  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:43.276  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:43.276  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:43.276  5601  5649 I jxcore-log: 
,11-04 22:32:44.307  5601  5649 I jxcore-log: 2016-11-04 21:32:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:44.307  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:44.307  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:44.307  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:44.307  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:44.307  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:44.307  5601  5649 I jxcore-log: 
,11-04 22:32:44.310  5601  5649 I jxcore-log: 2016-11-04 21:32:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:44.310  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:44.310  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:44.310  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:44.310  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:44.310  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:44.310  5601  5649 I jxcore-log: 
,11-04 22:32:45.341  5601  5649 I jxcore-log: 2016-11-04 21:32:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 22:32:45.341  5601  5649 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 22:32:45.341  5601  5649 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 22:32:45.341  5601  5649 I jxcore-log: emit@events.js:82:1
11-04 22:32:45.341  5601  5649 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 22:32:45.341  5601  5649 I jxcore-log: emit@events.js:82:1'
11-04 22:32:45.341  5601  5649 I jxcore-log: 
,11-04 22:32:45.352  5601  5649 E jxcore  : Error!: error is undefined
11-04 22:32:45.352  5601  5649 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 22:32:45.355  5601  5649 I jxcore-log: 2016-11-04 21:32:45 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 22:32:45.355  5601  5649 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-04 22:32:45.355  5601  5649 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 22:32:45.355  5601  5649 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 22:32:45.355  5601  5649 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 22:32:45.355  5601  5649 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 22:32:45.355  5601  5649 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 22:32:45.355  5601  5649 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
11-04 22:32:45.356  5601  5649 I jxcore-log: 2016-11-04 21:32:45 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 22:32:45.356  5601  5649 I jxcore-log: 
11-04 22:32:45.358  5601  5649 E jxcore-log: TypeError: 
,11-04 22:32:45.358  5601  5649 E jxcore-log: error is undefined
11-04 22:32:45.358  5601  5649 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-04 22:32:45.358  5601  5649 E jxcore-log: 
,11-04 22:32:45.453   928   939 I WindowState: WIN DEATH: Window{c176530 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 22:32:45.454   928  3524 D GraphicsStats: Buffer count: 2
,11-04 22:32:45.454   928  2855 D WifiService: Client connection lost with reason: 4
,11-04 22:32:45.464   928  3318 I ActivityManager: Process com.test.thalitest (pid 5601) has died
,11-04 22:32:45.463   526   526 I Zygote  : Process 5601 exited cleanly (139)
,11-04 22:32:45.477   928  3318 I ActivityManager: Start proc 6075:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 22:32:45.550  6075  6075 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 22:32:45.569  6075  6075 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 22:32:45.575  6075  6075 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2981-2983)
,11-04 22:32:45.575  6075  6075 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 22:32:45.584  6075  6075 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e4756ea}
,11-04 22:32:45.584  6075  6075 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 22:32:45.584  6075  6075 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 22:32:45.587  6075  6075 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 22:32:45.588  6075  6075 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 22:32:45.597  6075  6075 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 22:32:45.604  6075  6075 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 22:32:45.604  6075  6075 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 22:32:45.604  6075  6075 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 22:32:45.604  6075  6075 I Adreno  : Build Date                       : 12/06/15
11-04 22:32:45.604  6075  6075 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 22:32:45.604  6075  6075 I Adreno  : Local Branch                     : mybranch17112971
11-04 22:32:45.604  6075  6075 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 22:32:45.604  6075  6075 I Adreno  : Remote Branch                    : NONE
11-04 22:32:45.604  6075  6075 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 22:32:45.635   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@740e1f:true
,11-04 22:32:45.648   407   407 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33844]" dev="sockfs" ino=33844 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:45.648   407   407 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33844]" dev="sockfs" ino=33844 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:45.659  6075  6075 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 22:32:45.668  6075  6075 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 22:32:45.696  6075  6111 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 22:32:45.695   734   734 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[35229]" dev="sockfs" ino=35229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 22:32:45.695   734   734 W Binder_4: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[35229]" dev="sockfs" ino=35229 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:45.698  3700  3700 W Binder_9: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[16836]" dev="sockfs" ino=16836 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:45.698  3700  3700 W Binder_9: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[16836]" dev="sockfs" ino=16836 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 22:32:45.701  6075  6098 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 22:32:45.736  6075  6111 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 22:32:45.749   928  3700 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5601 uid 10077
,11-04 22:32:45.748  3700  3700 W Binder_9: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[36676]" dev="sockfs" ino=36676 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:45.752  3546  3546 I Keyboard.Facilitator: onFinishInput()
,11-04 22:32:45.748  3700  3700 W Binder_9: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[36676]" dev="sockfs" ino=36676 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 22:32:45.748   938   938 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[36675]" dev="sockfs" ino=36675 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:45.748   938   938 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[36675]" dev="sockfs" ino=36675 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:45.770   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +266ms (total +305ms)
,11-04 22:32:45.772  6075  6075 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6075
,11-04 22:32:45.826  6075  6075 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 22:32:45.878  6073  6073 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 22:32:45.894  6073  6073 D AndroidRuntime: CheckJNI is OFF
,11-04 22:32:45.915  6073  6073 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 22:32:45.941  6073  6073 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 22:32:45.956  6073  6073 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 22:32:45.964   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-04 22:32:45.964   928   941 I ActivityManager: Killing 6075:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 22:32:46.004   928   938 D GraphicsStats: Buffer count: 2
11-04 22:32:46.004   928  3524 I WindowState: WIN DEATH: Window{bddd77a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-04 22:32:46.066   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-04 22:32:46.066   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-04 22:32:46.068   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-04 22:32:46.068   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 22:32:46.068   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:32:46.068   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:32:46.068   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 22:32:46.068   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-04 22:32:46.068   928   951 I art     : Starting a blocking GC Explicit
11-04 22:32:46.069   928   941 I ActivityManager:   Force finishing activity ActivityRecord{17c10b8 u0 com.test.thalitest/.MainActivity t68}
,11-04 22:32:46.075   928  3057 W ActivityManager: Spurious death for ProcessRecord{4acdb88 0:com.test.thalitest/u0a77}, curProc for 6075: null
,11-04 22:32:46.168   928   951 I art     : Explicit concurrent mark sweep GC freed 47637(2MB) AllocSpace objects, 20(400KB) LOS objects, 33% free, 29MB/43MB, paused 2.166ms total 99.934ms
,11-04 22:32:46.188   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 22:32:46.192  6073  6073 I art     : System.exit called, status: 0
,11-04 22:32:46.192  6073  6073 I AndroidRuntime: VM exiting with result code 0.
,11-04 22:32:46.207   928   951 I ActivityManager: Start proc 6125:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-04 22:32:46.207   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 22:32:46.212   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-04 22:32:46.216  5983  5983 D BluetoothMapAppObserver: onReceive
11-04 22:32:46.216  5983  5983 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-04 22:32:46.218  3852  4029 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-04 22:32:46.222  3546  3546 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-04 22:32:46.225   928  2833 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-04 22:32:46.254  3546  6137 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 22:32:46.257  3303  6138 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-04 22:32:46.267  3546  6137 I Decoder : createOrResetDecoder
,11-04 22:32:46.276  3670  3670 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-04 22:32:46.281   313   313 W kworker/1:2: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 22:32:46.285   313   313 W kworker/1:2: type=1400 audit(0.0:136): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 22:32:46.303   928   938 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6075 uid 10077
,11-04 22:32:46.304  3546  3546 I Keyboard.Facilitator: onFinishInput()
11-04 22:32:46.305  3484  3484 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-04 22:32:46.306  3484  3484 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-04 22:32:46.306  3484  3484 E AndroidRuntime: FATAL EXCEPTION: main
11-04 22:32:46.306  3484  3484 E AndroidRuntime: Process: com.google.process.gapps, PID: 3484
11-04 22:32:46.306  3484  3484 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-04 22:32:46.306  3484  3484 E AndroidRuntime: 	... 8 more
,11-04 22:32:46.301   938   938 W Binder_1: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[28385]" dev="sockfs" ino=28385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 22:32:46.301   938   938 W Binder_1: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[28385]" dev="sockfs" ino=28385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 22:32:46.308   313   313 W kworker/1:2: type=1400 audit(0.0:139): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 22:32:46.311   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 22:32:46.312  3689  3807 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-04 22:32:46.313   928  6144 E DropBoxManagerService: Can't write: system_app_crash
11-04 22:32:46.313   928  6144 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 22:32:46.313   928  6144 E DropBoxManagerService: 	... 5 more
,11-04 22:32:46.315   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-04 22:32:46.316   928   940 E PackageManager: Failed to write settings, restoring backup
11-04 22:32:46.316   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-04 22:32:46.316   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-04 22:32:46.316   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-04 22:32:46.316   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-04 22:32:46.316   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-04 22:32:46.316   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 22:32:46.316   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:32:46.316   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 22:32:46.319   928   941 E DropBoxManagerService: Can't write: system_server_wtf
11-04 22:32:46.319   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 22:32:46.319   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 22:32:46.319   928   941 E DropBoxManagerService: 	... 13 more
,11-04 22:32:46.338   928  3524 I ActivityManager: Start proc 6145:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-04 22:32:46.339  3484  3484 I Process : Sending signal. PID: 3484 SIG: 9
11-04 22:32:46.340  3689  3807 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-04 22:32:46.340  3689  3807 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3689
11-04 22:32:46.340  3689  3807 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 22:32:46.340  3689  3807 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 22:32:46.341   928  3318 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-04 22:32:46.344   928  6154 E DropBoxManagerService: Can't write: system_app_crash
11-04 22:32:46.344   928  6154 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 22:32:46.344   928  6154 E DropBoxManagerService: 	... 5 more
11-04 22:32:46.349  3689  3807 I Process : Sending signal. PID: 3689 SIG: 9
,11-04 22:32:46.367   928  2855 D WifiService: Client connection lost with reason: 4
11-04 22:32:46.371  3303  3330 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj226FE8911) - 
11-04 22:32:46.372   928   938 I ActivityManager: Process com.google.process.gapps (pid 3484) has died
11-04 22:32:46.372   928   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
11-04 22:32:46.372   928   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
11-04 22:32:46.373   928   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
11-04 22:32:46.373   928   938 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 31000ms

```
