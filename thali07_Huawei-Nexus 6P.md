#### Test 948424290a7d259_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-22 17:27:45.841  3874  4245 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-22 17:27:45.917  3874  4245 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-22 17:27:46.253  5626  5626 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 17:27:46.258  5626  5626 D AndroidRuntime: CheckJNI is OFF
11-22 17:27:46.283  5626  5626 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 17:27:46.315  5626  5626 I Radio-JNI: register_android_hardware_Radio DONE
11-22 17:27:46.331  5626  5626 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-22 17:27:46.343   929  3876 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 17:27:46.362  5626  5626 D AndroidRuntime: Shutting down VM
11-22 17:27:46.372  3991  5625 W SearchService: Abort, client detached.
11-22 17:27:46.381  3991  3991 I HotwordDetector: Closing mic
11-22 17:27:46.381  3991  4225 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@58476f6
11-22 17:27:46.382  3991  4241 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 17:27:46.399   929  3859 I ActivityManager: Start proc 5635:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 17:27:46.458   512  4244 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 17:27:46.460   512  4244 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-22 17:27:46.464   512  4244 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 17:27:46.464   512  4244 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 17:27:46.465   512  3027 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 17:27:46.467  3991  4229 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 17:27:46.469  3991  4240 I MicroRecognitionRnrImpl: Detection finished
11-22 17:27:46.490  5635  5635 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-22 17:27:46.513  5635  5635 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-22 17:27:46.573  5635  5635 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 9259-9315)
11-22 17:27:46.573  5635  5635 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-22 17:27:46.609  5635  5635 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {45c2a5d}
11-22 17:27:46.610  5635  5635 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-22 17:27:46.610  5635  5635 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-22 17:27:46.613  5635  5635 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-22 17:27:46.614  5635  5635 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-22 17:27:46.662  5635  5635 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-22 17:27:46.671  5635  5635 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-22 17:27:46.672  5635  5635 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 17:27:46.672  5635  5635 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 17:27:46.672  5635  5635 I Adreno  : Build Date                       : 12/06/15
11-22 17:27:46.672  5635  5635 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 17:27:46.672  5635  5635 I Adreno  : Local Branch                     : mybranch17112971
11-22 17:27:46.672  5635  5635 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 17:27:46.672  5635  5635 I Adreno  : Remote Branch                    : NONE
11-22 17:27:46.672  5635  5635 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 17:27:46.712   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11f228:true
,11-22 17:27:46.745   725   725 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22300]" dev="sockfs" ino=22300 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.745   725   725 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22300]" dev="sockfs" ino=22300 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.759  5635  5635 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 17:27:46.767  5635  5635 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 17:27:46.795   726   726 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31294]" dev="sockfs" ino=31294 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.801  5635  5672 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-22 17:27:46.795   726   726 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31294]" dev="sockfs" ino=31294 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.801  3859  3859 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22311]" dev="sockfs" ino=22311 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 17:27:46.801  3859  3859 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22311]" dev="sockfs" ino=22311 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.806  5635  5659 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-22 17:27:46.840  5635  5672 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 17:27:46.921   939   939 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32489]" dev="sockfs" ino=32489 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.921   939   939 W Binder_1: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32489]" dev="sockfs" ino=32489 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.926   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +548ms
11-22 17:27:46.921  3859  3859 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32488]" dev="sockfs" ino=32488 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.928  3677  3677 I Keyboard.Facilitator: onFinishInput()
11-22 17:27:46.921  3859  3859 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32488]" dev="sockfs" ino=32488 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 17:27:46.958  5635  5635 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5635
,11-22 17:27:47.055  5635  5635 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 17:27:47.293  5635  5675 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -588510928
,11-22 17:27:47.304  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 17:27:47.304  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 17:27:47.304  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 17:27:47.304  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 17:27:47.304  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-22 17:27:47.304  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebdaf78 added. We now have 1 listener(s)
,11-22 17:27:47.309  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-22 17:27:47.309  5635  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 17:27:47.310  5635  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:27:47.310  5635  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-22 17:27:47.313  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9557b7 added. We now have 1 listener(s)
11-22 17:27:47.313  5635  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 17:27:47.318   929  2990 D WifiService: New client listening to asynchronous messages
,11-22 17:27:47.320  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 17:27:47.320  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-22 17:27:47.320  5635  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 17:27:47.320  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-22 17:27:47.320  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 17:27:47.320  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 17:27:47.320  5635  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 17:27:47.322  5635  5675 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 17:27:47.448  5635  5635 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 17:27:47.703  5635  5644 I art     : Background sticky concurrent mark sweep GC freed 76332(7MB) AllocSpace objects, 16(1076KB) LOS objects, 24% free, 24MB/32MB, paused 1.517ms total 181.898ms
,11-22 17:27:48.239  5635  5682 W jxcore-log: Initializing JXcore engine
,11-22 17:27:48.239  5635  5682 W jxcore-log: JXcore engine is ready
,11-22 17:27:48.258  5682  5682 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1443 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 17:27:48.258  5682  5682 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13428]" dev="sockfs" ino=13428 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-22 17:27:48.258  5682  5682 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-22 17:27:48.258  5682  5682 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32459]" dev="sockfs" ino=32459 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 17:27:48.271  5635  5682 W jxcore-log: Starting JXcore engine
,11-22 17:27:48.321  5635  5682 W jxcore-log: Platform android
11-22 17:27:48.321  5635  5682 W jxcore-log: 
,11-22 17:27:48.321  5635  5682 W jxcore-log: Process ARCH arm
11-22 17:27:48.321  5635  5682 W jxcore-log: 
,11-22 17:27:48.482   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:27:48.514  5635  5682 I jxcore-log: JXcore Cordova bridge is ready!
11-22 17:27:48.514  5635  5682 I jxcore-log: 
,11-22 17:27:48.514  5635  5682 W jxcore-log: JXcore engine is started
,11-22 17:27:48.520  5635  5675 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-22 17:27:48.526  5635  5635 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 17:27:50.014  3597  3597 I ConfigService: onDestroy
,11-22 17:27:50.683   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:27:51.385   929  3850 I ActivityManager: Killing 5416:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-22 17:27:51.429   929  3850 I ActivityManager: Killing 5075:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,11-22 17:27:51.684   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:27:52.686   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:27:53.687   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:27:54.688   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:27:55.689   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 17:27:58.212  5635  5682 I jxcore-log: 2016-11-22 16:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 17:27:58.212  5635  5682 I jxcore-log: 
,11-22 17:27:58.214  5635  5682 I jxcore-log: 2016-11-22 16:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 17:27:58.214  5635  5682 I jxcore-log: 
,11-22 17:27:58.219  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 17:27:58.219  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 17:27:58.221  5635  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 17:27:58.224  5635  5682 I jxcore-log: 2016-11-22 16:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 17:27:58.224  5635  5682 I jxcore-log: 
,11-22 17:27:58.225  5635  5682 I jxcore-log: 2016-11-22 16:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 17:27:58.225  5635  5682 I jxcore-log: 
,11-22 17:27:58.474  5635  5682 I jxcore-log: 2016-11-22 16:27:58 - DEBUG UnitTest_app: 'Running unit tests'
11-22 17:27:58.474  5635  5682 I jxcore-log: 
,11-22 17:27:58.475  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 17:27:58.475  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd94027 added. We now have 2 listener(s)
,11-22 17:27:58.476  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 17:27:58.476  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 17:27:58.476  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 17:27:58.476  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:27:58.476  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3662d4 added. We now have 2 listener(s)
11-22 17:27:58.476  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:27:58.477  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 17:27:58.478  5635  5682 D executeNativeTests: Running unit tests
,11-22 17:27:58.517  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:27:58.518  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed added. We now have 3 listener(s)
,11-22 17:27:58.518  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:27:58.518  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:27:58.518  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:27:58.519  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:27:58.519  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 added. We now have 3 listener(s)
,11-22 17:27:58.519  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:27:58.521  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 17:27:58.522  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 17:27:58.522  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 17:27:58.523  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 17:27:58.523  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 17:27:58.523  5635  5682 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-22 17:27:58.523  5635  5682 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
11-22 17:27:58.523  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-22 17:27:58.524  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 17:27:58.524  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 17:27:58.524  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 17:27:58.524  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:27:58.525  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:27:58.525  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:27:58.525  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:27:58.525  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 17:27:58.525  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:27:58.525  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed removed from the list
11-22 17:27:58.525  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:27:58.525  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 removed from the list
,11-22 17:27:58.525  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:27:58.525  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:27:58.525  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:27:58.526  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.526  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.526  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.526  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:27:58.526  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 17:27:58.526  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:27:58.526  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:27:58.527  5635  5682 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-22 17:27:58.527  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:27:58.527  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:27:58.527  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:27:58.528  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:27:58.528  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:27:58.528  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:27:58.528  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:27:58.528  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:27:58.528  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:27:58.528  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:27:58.528  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.528  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.528  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.528  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.528  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:27:58.528  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:27:58.528  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:27:58.529  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 17:27:58.531  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 17:27:58.532  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:27:58.532  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:27:58.532  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:27:58.532  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:27:58.532  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:27:58.532  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:27:58.532  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:27:58.532  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:27:58.532  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:27:58.532  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:27:58.532  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.533  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.533  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.533  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.533  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:27:58.533  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 17:27:58.533  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:27:58.533  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:27:58.533  5635  5682 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 17:27:58.534  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:27:58.534  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 17:27:58.541  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 17:27:58.542  5635  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 17:27:58.542  5635  5682 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 17:27:58.542  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:27:58.542  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 17:27:58.542  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 17:27:58.542  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:27:58.542  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 17:27:58.544  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:27:58.545  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 17:27:58.546  5635  5682 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 17:27:58.546  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 17:27:58.546  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:27:58.548  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.548  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 17:27:58.549  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 17:27:58.549  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 17:27:58.549  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 17:27:58.550  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-22 17:27:58.551  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 17:27:58.552  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.552  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 17:27:58.552  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 17:27:58.552  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 17:27:58.552  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 17:27:58.552  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.552  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:27:58.554  4675  4687 D BtGatt.GattService: registerClient() - UUID=6f7989d7-e68a-499e-98c2-31fd580cca33
11-22 17:27:58.555  4675  4737 D BtGatt.GattService: onClientRegistered() - UUID=6f7989d7-e68a-499e-98c2-31fd580cca33, clientIf=5
11-22 17:27:58.556  5635  5646 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 17:27:58.557  4675  4688 D BtGatt.GattService: start scan with filters
11-22 17:27:58.564  4675  4742 D BtGatt.ScanManager: handling starting scan
11-22 17:27:58.564  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 17:27:58.564  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.564  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 17:27:58.564  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.565  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 17:27:58.565  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 17:27:58.565  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 17:27:58.565  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.565  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.565  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 17:27:58.565  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 17:27:58.565  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.566  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.566  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.566  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.567  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.567  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.567  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:27:58.567  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.568  4675  4742 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:27:58.568  5635  5682 I io.jxcore.node.ConnectionHelper: start: OK
11-22 17:27:58.571  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.572  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:27:58.572  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.572  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 17:27:58.572  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:27:58.576  4675  4737 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 17:27:58.576  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:27:58.577  4675  4742 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 17:27:58.583  4675  4737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 17:27:58.584  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:27:58.584  4675  4742 D BtGatt.ScanManager: Starting BLE batch scan
11-22 17:27:58.584  4675  4742 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 17:27:58.595  4675  4737 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 17:27:58.595  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:27:58.602  4675  4737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 17:27:58.602  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:27:59.074  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-22 17:27:59.074  5635  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:27:59.074  5635  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 17:27:59.644   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 17:27:59.649   929  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-22 17:28:02.670   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 17:28:02.680   929  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-22 17:28:03.573  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 17:28:03.573  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:03.573  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-22 17:28:03.573  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:28:03.573  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 17:28:03.574  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:03.574  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 17:28:03.574  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 17:28:03.574  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.574  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-22 17:28:03.574  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 17:28:03.575  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:03.575  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.575  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:03.575  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 17:28:03.576  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:03.576  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:28:03.577  4675  4885 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 17:28:03.577  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-22 17:28:03.578  5635  5682 D BluetoothAdapter: STATE_ON
,11-22 17:28:03.578  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 17:28:03.579  4675  4885 D BtGatt.GattService: stopScan() - queue size =1
11-22 17:28:03.580  4675  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 17:28:03.580  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-22 17:28:03.580  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.580  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 17:28:03.580  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:03.580  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.581  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.581  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.581  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 17:28:03.581  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.581  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.581  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:03.581  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 17:28:03.582  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 17:28:03.582  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:28:03.582  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.584  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.584  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:28:03.584  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.584  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:03.584  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:03.584  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:28:03.585  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:28:03.585  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:03.585  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:03.585  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:03.585  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:03.585  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:03.585  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:03.585  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 17:28:03.585  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:03.586  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 17:28:03.586  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.586  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 17:28:03.586  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 17:28:03.587  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.587  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.587  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.587  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:28:03.588  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.588  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.595  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.595  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:28:03.595  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 17:28:03.603  4675  4675 D BtGatt.ScanManager: awakened up at time 96345
,11-22 17:28:03.649  4675  4737 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-22 17:28:03.649  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:03.649  4675  4737 D BtGatt.GattService: current time is 96391261264
11-22 17:28:03.649  4675  4737 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -93, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -91, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 17:28:03.651  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 17:28:03.652  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 17:28:03.653  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 17:28:03.653  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 17:28:03.653  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 17:28:03.653  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-22 17:28:03.658  4675  4737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 17:28:03.658  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:03.659  4675  4742 D BtGatt.ScanManager: stopping BLe Batch
,11-22 17:28:03.664  4675  4737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 17:28:03.664  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:03.664  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 17:28:03.666  3991  5683 W CronetSyncConnectionRcs: Upload content type not set.
,11-22 17:28:03.669  4675  4737 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 17:28:03.669  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:03.737  4859  4914 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-22 17:28:03.739  4859  4859 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-22 17:28:04.089  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 17:28:08.486   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:28:08.587  5635  5682 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 17:28:08.595  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 17:28:08.595  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 17:28:08.617  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 17:28:08.623  5635  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 17:28:08.623  5635  5682 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-22 17:28:08.623  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 17:28:08.623  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 17:28:08.623  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-22 17:28:08.623  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:28:08.624  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 17:28:08.629  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:08.632  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 17:28:08.633  5635  5682 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 17:28:08.633  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 17:28:08.633  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:08.640  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.640  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 17:28:08.641  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-22 17:28:08.641  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 17:28:08.641  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 17:28:08.645  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.645  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-22 17:28:08.645  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 17:28:08.645  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 17:28:08.645  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 17:28:08.645  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.646  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:28:08.649  4675  4885 D BtGatt.GattService: registerClient() - UUID=10909979-e3a0-4356-8a15-e4b422e3a730
11-22 17:28:08.650  4675  4737 D BtGatt.GattService: onClientRegistered() - UUID=10909979-e3a0-4356-8a15-e4b422e3a730, clientIf=5
11-22 17:28:08.650  5635  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 17:28:08.650  4675  4688 D BtGatt.GattService: start scan with filters
,11-22 17:28:08.655  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 17:28:08.655  4675  4742 D BtGatt.ScanManager: handling starting scan
11-22 17:28:08.656  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.656  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 17:28:08.656  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:08.656  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 17:28:08.656  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 17:28:08.656  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.656  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 17:28:08.657  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 17:28:08.657  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.657  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.657  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.657  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.657  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 17:28:08.657  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.660  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.660  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:28:08.660  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.660  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.660  5635  5682 I io.jxcore.node.ConnectionHelper: start: OK
11-22 17:28:08.660  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.662  4675  4737 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 17:28:08.662  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.662  4675  4742 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 17:28:08.662  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.662  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-22 17:28:08.662  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.663  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 17:28:08.663  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:08.663  5635  5682 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-22 17:28:08.663  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:08.663  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 17:28:08.663  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:28:08.663  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 17:28:08.663  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:08.663  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 17:28:08.663  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 17:28:08.663  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.663  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 17:28:08.664  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-22 17:28:08.664  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.664  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.664  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.664  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 17:28:08.664  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.664  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:28:08.665  4675  4688 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-22 17:28:08.665  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 17:28:08.666  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:28:08.666  4675  4885 D BtGatt.GattService: stopScan() - queue size =1
11-22 17:28:08.667  4675  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.667  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.668  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 17:28:08.668  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 17:28:08.668  4675  4737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 17:28:08.668  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.668  4675  4742 D BtGatt.ScanManager: Starting BLE batch scan
11-22 17:28:08.668  4675  4742 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 17:28:08.668  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:28:08.668  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.669  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.669  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:28:08.669  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.670  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.670  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:08.670  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:28:08.670  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:28:08.670  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:08.670  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:08.670  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:08.670  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:08.670  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:08.670  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:08.670  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 17:28:08.670  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:08.670  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-2,2 17:28:08.670  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.670  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 17:28:08.670  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 17:28:08.670  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.671  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.671  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.671  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:28:08.671  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.671  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.672  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.672  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.672  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.672  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.673  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.674  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.674  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.674  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.674  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:08.674  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:08.674  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:08.674  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:08.675  5635  5682 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 17:28:08.676  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 17:28:08.676  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 17:28:08.678  4675  4737 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 17:28:08.678  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 17:28:08.683  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 17:28:08.684  4675  4737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 17:28:08.684  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.684  5635  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 17:28:08.685  5635  5682 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 17:28:08.685  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 17:28:08.685  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 17:28:08.685  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 17:28:08.685  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 17:28:08.685  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:28:08.685  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 17:28:08.687  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 17:28:08.687  5635  5682 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-22 17:28:08.687  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 17:28:08.687  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:08.690  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:08.690  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.690  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 17:28:08.690  4675  4737 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 17:28:08.690  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.691  4675  4737 E BtGatt.ContextMap: Context not found for ID 5
11-22 17:28:08.691  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 17:28:08.691  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 17:28:08.691  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 17:28:08.695  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:08.695  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 17:28:08.695  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 17:28:08.695  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 17:28:08.695  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 17:28:08.695  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.695  5635  5682 D BluetoothAdapter: STATE_ON
,11-22 17:28:08.697  4675  4737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 17:28:08.697  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.697  4675  4742 D BtGatt.ScanManager: stopping BLe Batch
,11-22 17:28:08.698  4675  4885 D BtGatt.GattService: registerClient() - UUID=a43fb097-83e4-4d8b-8076-3a8f83afe430
,11-22 17:28:08.701  4675  4737 D BtGatt.GattService: onClientRegistered() - UUID=a43fb097-83e4-4d8b-8076-3a8f83afe430, clientIf=5
,11-22 17:28:08.702  5635  5646 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 17:28:08.702  4675  4688 D BtGatt.GattService: start scan with filters
11-22 17:28:08.703  4675  4737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 17:28:08.703  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.704  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 17:28:08.704  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 17:28:08.704  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.704  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 17:28:08.704  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.705  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 17:28:08.705  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 17:28:08.705  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.705  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 17:28:08.705  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 17:28:08.705  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.705  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.705  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.705  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.706  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 17:28:08.706  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.708  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.708  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:28:08.708  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.708  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:08.708  5635  5682 I io.jxcore.node.ConnectionHelper: start: OK
11-22 17:28:08.708  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.709  4675  4737 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 17:28:08.710  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.710  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.710  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.710  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 17:28:08.710  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 17:28:08.712  4675  4742 D BtGatt.ScanManager: handling starting scan
,11-22 17:28:08.717  4675  4737 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-22 17:28:08.717  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:08.717  4675  4742 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 17:28:08.721  4675  4737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 17:28:08.722  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:08.722  4675  4742 D BtGatt.ScanManager: Starting BLE batch scan
11-22 17:28:08.722  4675  4742 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 17:28:08.731  4675  4737 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 17:28:08.731  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:08.736  4675  4737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 17:28:08.736  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:09.212  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-22 17:28:09.212  5635  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:28:09.212  5635  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 17:28:13.708  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 17:28:13.709  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-22 17:28:13.709  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-22 17:28:13.709  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:28:13.709  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 17:28:13.710  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:13.710  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 17:28:13.710  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 17:28:13.710  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.710  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 17:28:13.710  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 17:28:13.711  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:13.711  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.711  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.711  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-22 17:28:13.712  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.713  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:28:13.714  4675  4687 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 17:28:13.715  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 17:28:13.717  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:28:13.718  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 17:28:13.718  4675  4885 D BtGatt.GattService: stopScan() - queue size =1
11-22 17:28:13.719  4675  4687 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 17:28:13.720  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 17:28:13.720  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.721  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 17:28:13.721  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.721  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.722  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:13.722  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.722  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 17:28:13.722  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.722  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.723  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.723  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 17:28:13.723  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 17:28:13.725  4675  4675 D BtGatt.ScanManager: awakened up at time 106467
,11-22 17:28:13.725  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:28:13.726  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.729  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.729   929  3883 I ActivityManager: Killing 5430:com.android.chrome/u0a39 (adj 15): empty #17
11-22 17:28:13.729  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:28:13.729  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.729  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:13.730  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:13.730  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:13.730  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 17:28:13.730  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:28:13.730  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-22 17:28:13.730  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 17:28:13.730  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:28:13.730  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 17:28:13.730  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-22 17:28:13.730  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:28:13.731  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 17:28:13.731  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:28:13.732  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 17:28:13.732  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:28:13.733  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 17:28:13.763  4675  4737 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-22 17:28:13.763  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:28:13.763  4675  4737 D BtGatt.GattService: current time is 106505645417
11-22 17:28:13.764  4675  4737 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -92, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -90, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -84, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -92, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 17:28:13.764  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 17:28:13.764  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 17:28:13.764  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 17:28:13.764  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-22 17:28:13.765  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 17:28:13.765  4675  4737 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-22 17:28:13.770  4675  4737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 17:28:13.770  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:13.770  4675  4742 D BtGatt.ScanManager: stopping BLe Batch
,11-22 17:28:13.776  4675  4737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 17:28:13.776  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:13.776  4675  4742 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 17:28:13.780  4675  4737 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 17:28:13.780  4675  4737 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:28:14.232  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 17:28:14.232  5635  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:14.232  5635  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 17:28:18.731  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 17:28:18.731  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.732  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:28:18.732  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 17:28:18.732  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 17:28:18.732  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:28:18.732  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.733  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
,11-22 17:28:18.733  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:18.733  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:18.733  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:18.733  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 17:28:18.737  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.737  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.743  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.743  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.744  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.744  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.744  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.744  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.744  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:18.749  5635  5682 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-22 17:28:18.750  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 17:28:18.750  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.751  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:28:18.751  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.751  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.751  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.751  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.751  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.752  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:18.752  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.752  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.754  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.755  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.755  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.755  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.755  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.755  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.755  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:18.757  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 17:28:18.757  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 17:28:18.758  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.758  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:18.758  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.758  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.758  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.758  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.758  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.758  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:18.758  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.759  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.761  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.761  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.761  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.762  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.762  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.762  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.762  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.763  5635  5682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-22 17:28:18.763  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:18.763  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.763  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:28:18.763  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.763  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.763  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.764  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.764  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.764  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:18.764  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.764  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.766  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.766  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.766  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.766  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 17:28:18.766  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.766  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.767  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:18.769  5635  5682 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-22 17:28:18.769  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:18.769  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 17:28:18.769  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:18.769  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.769  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.769  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.770  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.770  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:18.770  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:18.770  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.770  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.772  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.772  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.772  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.772  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.772  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 17:28:18.772  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.772  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.773  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 17:28:18.773  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 17:28:18.773  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 17:28:18.774  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 17:28:18.774  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 17:28:18.774  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 17:28:18.774  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 17:28:18.774  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 17:28:18.774  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 17:28:18.774  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:18.774  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.774  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:28:18.774  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.774  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.775  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.775  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.775  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.775  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:18.776  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.777  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:18.779  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.779  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.779  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.779  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.779  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.779  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:18.779  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.780  5635  5682 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 17:28:18.780  5635  5682 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 17:28:18.780  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-22 17:28:18.783  5635  5682 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 17:28:18.784  5635  5682 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 17:28:18.784  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 17:28:18.785  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-22 17:28:18.786  5635  5682 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-22 17:28:18.786  5635  5682 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 17:28:18.786  5635  5682 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-22 17:28:18.786  5635  5682 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 17:28:18.786  5635  5682 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 17:28:18.786  5635  5682 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-22 17:28:18.787  5635  5682 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 17:28:18.787  5635  5682 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 17:28:18.787  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-22 17:28:18.791  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-22 17:28:18.793  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-22 17:28:18.793  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-22 17:28:18.794  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-22 17:28:18.794  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-22 17:28:18.794  5635  5682 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-22 17:28:18.794  5635  5682 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 17:28:18.794  5635  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-22 17:28:18.794  5635  5682 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-22 17:28:18.795  5635  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-22 17:28:18.795  5635  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-22 17:28:18.795  5635  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-22 17:28:18.796  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:18.796  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.796  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:18.796  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.796  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.796  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-22 17:28:18.798  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.798  5635  5687 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-22 17:28:18.798  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.798  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.798  5635  5687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 17:28:18.798  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:18.801  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.795  4687  4687 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31337]" dev="sockfs" ino=31337 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 17:28:18.801  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.801  5635  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-22 17:28:18.801  5635  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-22 17:28:18.801  5635  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-22 17:28:18.802  5635  5688 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-22 17:28:18.802  5635  5687 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-22 17:28:18.802  5635  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-22 17:28:18.795  4687  4687 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31337]" dev="sockfs" ino=31337 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 17:28:18.802  5635  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-22 17:28:18.802  4675  4883 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
11-22 17:28:18.802  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.802  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.802  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.802  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.802  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.802  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.802  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.803  5635  5682 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-22 17:28:18.804  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:18.804  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.804  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:18.804  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.804  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.804  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.804  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.804  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.804  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:18.804  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.804  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.806  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.806  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.806  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.806  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.806  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.806  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.806  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.807  5635  5682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-22 17:28:18.807  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:18.807  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.808  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:18.808  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.808  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.808  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.808  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.808  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.808  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:18.808  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.808  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.809  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.810  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.810  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.810  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.810  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.810  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.810  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.810  5635  5682 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-22 17:28:18.810  5635  5682 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-22 17:28:18.811  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 17:28:18.811  5635  5682 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-22 17:28:18.811  5635  5682 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 17:28:18.811  5635  5682 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-22 17:28:18.811  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 17:28:18.811  5635  5682 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-22 17:28:18.811  5635  5682 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 17:28:18.811  5635  5682 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 17:28:18.811  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 17:28:18.811  5635  5682 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-22 17:28:18.811  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:18.811  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:18.811  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:18.811  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.811  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.811  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.811  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.812  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.812  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:18.812  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.812  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.812  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.813  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.813  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:18.813  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:18.813  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:18.813  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.813  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.813  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:18.813  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:18.813  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:18.813  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:18.813  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:18.814  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:20.690   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-22 17:28:20.690   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 17:28:20.848   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 17:28:23.814  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:23.815  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.815  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:23.815  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:23.815  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:23.816  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 17:28:23.816  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:23.816  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:28:23.816  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:23.816  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:23.817  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:23.817  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:23.817  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.817  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:23.817  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.818  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:23.821  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:23.821  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.821  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.822  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:23.822  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:23.822  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.822  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:23.826  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-22 17:28:23.827  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:28:23.827  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 17:28:23.833  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-22 17:28:23.834  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-22 17:28:23.834  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-22 17:28:23.835  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 17:28:23.835  5635  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 17:28:23.835  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-22 17:28:23.835  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 17:28:23.835  5635  5635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-22 17:28:23.835  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:23.836  5635  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 17:28:23.831  4688  4688 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30626]" dev="sockfs" ino=30626 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 17:28:23.836  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 17:28:23.836  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 17:28:23.836  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-22 17:28:23.836  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 17:28:23.836  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 17:28:23.836  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 17:28:23.835  4688  4688 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30626]" dev="sockfs" ino=30626 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-22 17:28:23.837  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:23.837  5635  5635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-22 17:28:23.837  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.837  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 17:28:23.837  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.837  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 17:28:23.837  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-22 17:28:23.837  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.838  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.838  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 17:28:23.839  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.839  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.839  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.839  5635  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-22 17:28:23.839  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:23.839  5635  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 17:28:23.839  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:23.839  5635  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 17:28:23.839  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 17:28:23.839  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:28:23.839  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:23.840  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:28:23.840  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:23.840  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 17:28:23.840  5635  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-22 17:28:23.840  5635  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:23.840  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:23.840  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.840  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.840  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:23.840  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:23.841  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.843  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.843  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.844  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:23.844  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:23.844  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:23.844  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.844  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.846  5635  5682 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-22 17:28:23.847  5635  5682 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 17:28:23.847  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-22 17:28:23.847  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 17:28:23.847  5635  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 17:28:23.847  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:23.847  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:23.847  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:23.848  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:23.848  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 17:28:23.848  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:23.848  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.848  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:23.848  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:23.848  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.848  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:23.850  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.850  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.851  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.851  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:23.851  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:23.851  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.851  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:23.855  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:23.855  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:28:23.855  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 17:28:23.856  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:23.856  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:23.856  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:23.856  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.856  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.856  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:23.856  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.856  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.857  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.857  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.858  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:28:23.858  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:23.858  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:28:23.858  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.858  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
,11-22 17:28:23.860  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:28:23.860  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 17:28:23.860  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:28:23.860  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:28:23.860  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:28:23.860  5635  5682 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@122deed not in the list
11-22 17:28:23.860  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.860  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.860  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:23.860  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.860  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.862  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.862  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.862  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:28:23.862  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:28:23.862  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 17:28:23.862  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:28:23.862  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4135122 not in the list
11-22 17:28:23.864  5635  5682 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-22 17:28:23.864  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 17:28:23.864  5635  5682 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-22 17:28:23.864  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 17:28:23.864  5635  5682 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-22 17:28:23.864  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 17:28:23.867  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-22 17:28:23.867  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-22 17:28:23.868  5635  5682 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-22 17:28:23.868  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 17:28:23.868  5635  5682 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-22 17:28:23.868  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 17:28:23.868  5635  5682 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-22 17:28:23.868  5635  5682 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-22 17:28:23.869  5635  5682 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-22 17:28:23.869  5635  5682 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-22 17:28:23.870  5635  5682 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-22 17:28:23.870  5635  5682 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-22 17:28:23.870  5635  5682 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-22 17:28:23.870  5635  5682 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-22 17:28:23.871  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:28:23.871  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7fc53a3 added. We now have 3 listener(s)
,11-22 17:28:23.871  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 17:28:23.873  5635  5682 D BluetoothAdapter: enable(): BT is already enabled..!
,11-22 17:28:23.873   929  3859 D WifiService: setWifiEnabled: true pid=5635, uid=10077
11-22 17:28:23.873   929  3859 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 17:28:23.927  4675  4881 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-22 17:28:23.927  4675  4881 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-22 17:28:24.341  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 17:28:25.691   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:26.692   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:26.892   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 17:28:27.693   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:28.694   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:28.879  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:28:28.880  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afd76a0 added. We now have 4 listener(s)
11-22 17:28:28.880  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 17:28:28.893  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:28.893  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afd76a0 removed from the list
,11-22 17:28:28.893  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:28.896  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:28:28.897  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d07259 added. We now have 4 listener(s)
11-22 17:28:28.897  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 17:28:28.900  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:28.900  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d07259 removed from the list
11-22 17:28:28.901  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:28.902  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:28:28.903  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dfe1e added. We now have 4 listener(s)
11-22 17:28:28.903  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 17:28:28.909   929  3850 D WifiService: setWifiEnabled: false pid=5635, uid=10077
,11-22 17:28:28.909   929  3850 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 17:28:28.917   929  2989 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-22 17:28:28.918   929  2989 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-22 17:28:28.918   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 17:28:28.918   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 17:28:28.925  4675  4733 D BluetoothAdapterState: Current state: ON, message: 23
,11-22 17:28:28.925  4675  4733 D BluetoothAdapterProperties: Setting state to 13
,11-22 17:28:28.925  4675  4733 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-22 17:28:28.928  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 17:28:28.928  4675  4733 D BluetoothAdapterProperties: onBluetoothDisable()
,11-22 17:28:28.928  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 17:28:28.929  4675  4733 I BluetoothAdapterState: Entering PendingCommandState
11-22 17:28:28.936  4675  4675 D BluetoothMapService: onReceive
11-22 17:28:28.936  4675  4675 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 17:28:28.936  4675  4675 D BluetoothMapService: STATE_TURNING_OFF
11-22 17:28:28.936  4675  4675 D BluetoothMapService: MAP Service closeService in
11-22 17:28:28.937  4675  4675 D BluetoothMapMasInstance0: MAP Service shutdown
,11-22 17:28:28.937  4675  4675 D ObexServerSockets0: shutdown(block = true)
11-22 17:28:28.937   507   926 D CommandListener: Clearing all IP addresses on wlan0
11-22 17:28:28.937  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 17:28:28.938  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 17:28:28.938  4675  4883 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 17:28:28.938  4675  4897 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-22 17:28:28.938   929  5392 D DhcpClient: Clearing IP address
11-22 17:28:28.939   507   926 D CommandListener: Setting iface cfg
11-22 17:28:28.939  4675  4896 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-22 17:28:28.940  4675  4675 I BtOppRfcommListener: stopping Accept Thread
11-22 17:28:28.941  4675  5321 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 17:28:28.941  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 17:28:28.941  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 17:28:28.941  4675  5321 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-22 17:28:28.942   929  5393 D DhcpClient: Receive thread stopped
11-22 17:28:28.942  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:28.942  5635  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 17:28:28.943  5635  5682 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 17:28:28.947  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:28.950  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:28.955   929   942 I ActivityManager: Start proc 5693:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-22 17:28:28.957  3597  5443 V NativeCrypto: Read error: ssl=0x7f85d85700: I/O error during system call, Connection timed out
,11-22 17:28:28.959  3597  5443 V NativeCrypto: SSL shutdown failed: ssl=0x7f85d85700: I/O error during system call, Broken pipe
11-22 17:28:28.960   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 17:28:28.960   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-22 17:28:28.965  4675  4737 D BluetoothAdapterProperties: Scan Mode:20
,11-22 17:28:28.965   929  2991 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-22 17:28:28.966  4675  4733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 17:28:28.966   533   533 E Parcel  : Reading a NULL string not supported here.
11-22 17:28:28.969  3769  3908 W QCNEJ   : |CORE| network lost: 100
11-22 17:28:28.970   929   929 D RttService: SCAN_AVAILABLE : 1
11-22 17:28:28.970  3769  3908 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-22 17:28:28.970   929  3099 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 17:28:28.971  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 17:28:28.971  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 17:28:28.973  4675  4675 D HeadsetService: Received stop request...Stopping profile...
,11-22 17:28:28.974  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:28.974  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 17:28:28.974   929  2989 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 17:28:28.975   929   929 D BluetoothHeadset: Proxy object disconnected
,11-22 17:28:28.975   929   929 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:28.975  3146  3158 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:28.976  4675  4675 D A2dpService: Received stop request...Stopping profile...
11-22 17:28:28.976  3797  3812 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:28.976   929   929 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:28.976  4675  4888 D A2dpStateMachine: Exit Disconnected: -1
11-22 17:28:28.977   929   929 D BluetoothA2dp: Proxy object disconnected
,11-22 17:28:28.978  4675  4675 D HidService: Received stop request...Stopping profile...
11-22 17:28:28.978  4675  4675 D HidService: Stopping Bluetooth HidService
,11-22 17:28:28.979  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:28.979  4675  4675 V BluetoothAdapterState: isTurningOn()=false
,11-22 17:28:28.979  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:28.979  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:28.980  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 17:28:28.980   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 17:28:28.981  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-22 17:28:28.981  4675  4737 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 17:28:28.982  4675  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:28.982  4675  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 17:28:28.982  4675  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 17:28:28.982  4675  4737 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-22 17:28:28.982  4675  4675 D HealthService: Received stop request...Stopping profile...
,11-22 17:28:28.985  4675  4675 D PanService: Received stop request...Stopping profile...
,11-22 17:28:28.986  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:28.986  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:28.986  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:28.987  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:28.990  4675  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:28.990  4675  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:28.991  4675  4737 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 17:28:28.991  4675  4881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 17:28:28.991  4675  4881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 17:28:28.991  4675  4881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-22 17:28:28.991  4675  4881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 17:28:28.991  4675  4675 D BluetoothMapService: Received stop request...Stopping profile...
11-22 17:28:28.991  4675  4675 D BluetoothMapService: stop()
11-22 17:28:28.992  4675  4675 D BluetoothMapAppObserver: deinitObservers()
11-22 17:28:28.992  4675  4675 D BluetoothMapAppObserver: removeReceiver()
11-22 17:28:28.993  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:28.993  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:28.993  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:28.993  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:28.994  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 17:28:28.994  4675  4737 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 17:28:28.994  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 17:28:28.995  4675  4675 D SapService: Received stop request...Stopping profile...
11-22 17:28:28.995  4675  4675 V SapService: stop()
11-22 17:28:28.996  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:28.996  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:28.996  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:28.996  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:28.997  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 17:28:28.997  4675  4737 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 17:28:28.997  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 17:28:28.997  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:28.998  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:28.998  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:28.998  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:29.001  3146  3146 D HeadsetProfile: Bluetooth service disconnected
11-22 17:28:29.003  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-22 17:28:29.003  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 17:28:29.003  3146  3146 D BluetoothA2dp: Proxy object disconnected
11-22 17:28:29.004  3146  3146 D BluetoothInputDevice: Proxy object disconnected
11-22 17:28:29.004  3146  3146 D HidProfile: Bluetooth service disconnected
11-22 17:28:29.004  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 17:28:29.004  3146  3146 D PanProfile: Bluetooth service disconnected
11-22 17:28:29.004  3146  3146 D BluetoothMap: Proxy object disconnected
11-22 17:28:29.004  3146  3146 D MapProfile: Bluetooth service disconnected
,11-22 17:28:29.005  4675  4675 D BluetoothMapService: MAP Service closeService in
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:29.006  4675  4675 D BluetoothMapService: cleanup()
11-22 17:28:29.006  4675  4675 D BluetoothMapService: MAP Service closeService in
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:29.006  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:29.009   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:28:29.011  4675  4733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 17:28:29.011  4675  4733 D BluetoothAdapterProperties: Setting state to 15
11-22 17:28:29.011  4675  4733 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 17:28:29.012  4675  4733 I BluetoothAdapterState: Entering BleOnState
11-22 17:28:29.012  3146  4009 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-22 17:28:29.013  3146  3361 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:29.013   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 17:28:29.013  3146  3158 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 17:28:29.014  3797  3996 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:29.014   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:29.014   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:29.014  3146  3159 D BluetoothMap: onBluetoothStateChange: up=false
11-22 17:28:29.015   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 17:28:29.015  3146  4009 D BluetoothPan: onBluetoothStateChange on: false
11-22 17:28:29.015  3146  3361 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 17:28:29.016  4675  4733 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 17:28:29.016  4675  4733 D BluetoothAdapterProperties: Setting state to 16
11-22 17:28:29.016  4675  4733 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 17:28:29.017  4675  4733 D BluetoothAdapterProperties: onBleDisable
11-22 17:28:29.017  4675  4733 I BluetoothAdapterState: Entering PendingCommandState
11-22 17:28:29.017  4675  4734 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 17:28:29.018  4675  4881 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 17:28:29.018  4675  4737 D BluetoothAdapterProperties: Scan Mode:20
,11-22 17:28:29.018  4675  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:29.020  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:29.021  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:29.033  5693  5693 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-22 17:28:29.036   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:28:29.037   507   926 D CommandListener: Clearing all IP addresses on wlan0
,11-22 17:28:29.037   507   926 D TetherController: Setting IP forward enable = 0
11-22 17:28:29.038   929  2991 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-22 17:28:29.039   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 17:28:29.042   929  2989 D DhcpClient: doQuit
,11-22 17:28:29.042   929  2989 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 17:28:29.043  3478  3478 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 17:28:29.044   929   946 D Tethering: MasterInitialState.processMessage what=3
11-22 17:28:29.044   929  5392 D DhcpClient: onQuitting
11-22 17:28:29.045  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 17:28:29.045  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 17:28:29.046  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:29.046  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 17:28:29.048  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:29.050  5271  5271 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9373d19 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-22 17:28:29.052  3991  3991 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-22 17:28:29.054  5063  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 17:28:29.054  5063  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 17:28:29.054  5063  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 17:28:29.054  5063  5085 E SarControlService: no key has been found,reset the power
11-22 17:28:29.054  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 17:28:29.054  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 17:28:29.055  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 17:28:29.055  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 17:28:29.055  5088  5088 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 17:28:29.057  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-22 17:28:29.057  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 17:28:29.057  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 17:28:29.057  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 17:28:29.057  5088  5088 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 17:28:29.060  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000ea03000000000000ffffffff]
11-22 17:28:29.060  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 17:28:29.060  5088  5102 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-22 17:28:29.062  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 17:28:29.062  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 17:28:29.063  3478  3478 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-22 17:28:29.066  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000eb03000000000000ffffffff]
,11-22 17:28:29.066  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 17:28:29.066  5088  5102 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-22 17:28:29.066  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 17:28:29.067  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-22 17:28:29.069  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 17:28:29.071  3478  3478 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-22 17:28:29.075   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5249f39:true
11-22 17:28:29.076  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 17:28:29.088   929   939 I ActivityManager: Start proc 5721:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-22 17:28:29.097  3478  3478 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 17:28:29.100   507   926 E Netd    : netlink response contains error (No such file or directory)
,11-22 17:28:29.102   507   926 D TetherController: Setting IP forward enable = 0
11-22 17:28:29.102   929  2991 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-22 17:28:29.109  3478  3478 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 17:28:29.111  5693  5693 D LocalBluetoothProfileManager: Adding local MAP profile
,11-22 17:28:29.120  5693  5693 D BluetoothMap: Create BluetoothMap proxy object
,11-22 17:28:29.131  5693  5693 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-22 17:28:29.138  5721  5721 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-22 17:28:29.149  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,11-22 17:28:29.151   929  3883 I ActivityManager: Killing 4504:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-22 17:28:29.213   929  2989 D wifi    : In wifi stop Hal
,11-22 17:28:29.213  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 17:28:29.213   929  2989 D wifi    : halHandle = 0x7f6afc3900, mVM = 0x7f8760d140, mCls = 0x100a02
11-22 17:28:29.213   929  3476 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 17:28:29.213   929  3476 D WifiHAL : Got a signal to exit!!!
11-22 17:28:29.213   929  3476 I WifiHAL : Exit wifi_event_loop
,11-22 17:28:29.214   929  2989 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 17:28:29.214   929  2989 E WifiHAL : Event processing terminated
11-22 17:28:29.214   929  2989 D wifi    : In wifi cleaned up handler
11-22 17:28:29.214   929  2989 I WifiHAL : Internal cleanup completed
11-22 17:28:29.215  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:29.215  4057  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 17:28:29.224  4675  4737 I bt_hci  : shut_down
,11-22 17:28:29.229  4675  4744 D bt_hwcfg: hw_epilog_process
,11-22 17:28:29.229  4675  4744 I bt_vendor: low_power_mode_cb
,11-22 17:28:29.232  4675  4744 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-22 17:28:29.232  4675  4744 I bt_vendor: epilog_cb
11-22 17:28:29.232  4675  4744 I bt_hci  : epilog_finished_callback
11-22 17:28:29.234  4675  4737 I bt_hci_h4: hal_close
11-22 17:28:29.234   929  3476 D wifi    : set interface wlan0 flags (DOWN)
11-22 17:28:29.234  4675  4737 I bt_userial_vendor: device fd = 54 close
11-22 17:28:29.234   929  2989 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 17:28:29.328  5721  5721 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.328  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.329  5721  5721 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared,.f.a.a(PG:48)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.329  5721  5721 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(Ac,tivityThread.java:5422)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.329  5721  5721 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.e.b(PG:170)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.329  5721  5721 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.k.d(PG:583)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.e.b(PG:170)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.329  5721  5721 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.329  5721  5721 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.File.exists(File.java:361)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.329  5721  5721 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:28:29.329  5721  5721 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:28:29.334  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 17:28:29.341  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 17:28:29.344  5693  5693 D DockEventReceiver: finishStartingService: stopping service
11-22 17:28:29.346   929  3432 I ActivityManager: Killing 5138:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-22 17:28:29.376  3874  3874 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 17:28:29.377  4675  4734 D bt_stack_manager: event_shut_down_stack finished.
11-22 17:28:29.377  4675  4733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-22 17:28:29.379  4675  4675 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 17:28:29.379  4675  4733 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-22 17:28:29.379  3874  3874 D SystemUpdateService: onCreate
11-22 17:28:29.379  4675  4675 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 17:28:29.379  4675  4675 D BtGatt.GattService: stop()
11-22 17:28:29.379  4675  4675 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 17:28:29.381  4675  4675 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:29.381  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:29.381  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:29.381  4675  4675 V BluetoothAdapterState: isBleTurningOff()=true
11-22 17:28:29.381  4675  4733 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 17:28:29.381  4675  4733 D BluetoothAdapterProperties: Setting state to 10
11-22 17:28:29.382  4675  4733 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 17:28:29.382  4675  4733 I BluetoothAdapterState: Entering OffState
11-22 17:28:29.382   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-22 17:28:29.387  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-22 17:28:29.387  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 17:28:29.387  4675  4675 I BluetoothServiceJni: cleanupNative: return from cleanup
11-22 17:28:29.389  4675  4734 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-22 17:28:29.390  3874  3874 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-22 17:28:29.401  4675  4734 D bt_stack_manager: event_clean_up_stack finished.
11-22 17:28:29.402  3874  3874 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-22 17:28:29.412  3874  5414 I iu.UploadsManager: num queued entries: 0
,11-22 17:28:29.412  3874  5414 I iu.UploadsManager: num updated entries: 0
11-22 17:28:29.413  3874  5414 I iu.SyncManager: NEXT; no task
,11-22 17:28:29.414  4675  4675 I art     : System.exit called, status: 0
11-22 17:28:29.414  4675  4675 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 17:28:29.430  3874  3874 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-22 17:28:29.431  3874  3874 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 17:28:29.432  3874  5757 I SystemUpdateService: active receiver: enabled
,11-22 17:28:29.436   929   946 D Tethering: InitialState.processMessage what=4
,11-22 17:28:29.441  3874  5757 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 17:28:29.443   929  3883 I ActivityManager: Start proc 5759:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-22 17:28:29.444   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 17:28:29.446  3874  5757 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-22 17:28:29.447  3874  5757 I SystemUpdateService: now status is 0 (complete)
11-22 17:28:29.447  3874  5757 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 17:28:29.447  3874  5757 I SystemUpdateService: file has been verified
11-22 17:28:29.447  3874  5757 I SystemUpdateService: OTA package size = 21989297
,11-22 17:28:29.449   929  3169 I ActivityManager: Process com.android.bluetooth (pid 4675) has died
,11-22 17:28:29.487  5759  5759 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-22 17:28:29.492  5759  5759 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 17:28:29.500  5759  5759 D SprintDMHelper: simOperator: 
11-22 17:28:29.500  5759  5759 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 17:28:29.503  3874  5757 I SystemUpdateService: showing system update notification
,11-22 17:28:29.513   929  3859 I ActivityManager: Start proc 5771:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-22 17:28:29.524   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 17:28:29.546  3874  3874 D SystemUpdateService: onDestroy
,11-22 17:28:29.550   929  3850 I ActivityManager: Killing 5463:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-22 17:28:29.631  5015  5785 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 17:28:29.639   929  3859 I ActivityManager: Start proc 5786:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-22 17:28:29.643   929  3883 I ActivityManager: Killing 5271:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-22 17:28:29.695   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:29.705  5786  5786 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-22 17:28:29.714   929  3156 I ActivityManager: Killing 3913:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-22 17:28:29.789  5721  5750 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-22 17:28:29.797   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cd73963:true
,11-22 17:28:30.695   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 17:28:33.946   929  3169 D WifiService: setWifiEnabled: true pid=5635, uid=10077
,11-22 17:28:33.946   929  3169 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 17:28:33.953   507   926 D SoftapController: Softap fwReload - Ok
,11-22 17:28:33.960   507   926 D CommandListener: Setting iface cfg
,11-22 17:28:33.960   507   926 D CommandListener: Trying to bring down wlan0
,11-22 17:28:33.962   507   926 D CommandListener: Clearing all IP addresses on wlan0
,11-22 17:28:33.969   929  2989 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 17:28:34.536   929  2989 D wifi    : set interface wlan0 flags (UP)
,11-22 17:28:34.539   929  2989 I WifiHAL : Initializing wifi
11-22 17:28:34.539   929  2989 I WifiHAL : Creating socket
11-22 17:28:34.543   929  2989 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-22 17:28:34.543   929  2989 D wifi    : Did set static halHandle = 0x7f6afc3900
11-22 17:28:34.543   929  2989 D wifi    : halHandle = 0x7f6afc3900, mVM = 0x7f8760d140, mCls = 0x2019ba
11-22 17:28:34.544   929  2989 D wifi    : array field set
11-22 17:28:34.544   929  2989 I WifiNative-HAL: interface[0] = wlan0
11-22 17:28:34.541   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-22 17:28:34.548   929  5803 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547255761152
11-22 17:28:34.548   929  5803 D wifi    : waitForHalEvents called, vm = 0x7f8760d140, obj = 0x2019ba, env = 0x7f7001e440
,11-22 17:28:34.604  5804  5804 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 17:28:34.648   929  2989 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 17:28:34.653  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:34.659  5804  5804 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 17:28:34.709  5804  5804 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 17:28:34.709  5804  5804 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 17:28:34.728   929  2989 D WifiConfigStore: Loading config and enabling all networks 
,11-22 17:28:34.729  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 17:28:34.729  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 17:28:34.729  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:34.730  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 17:28:34.754   929  2989 D WifiConfigStore: loaded 0 passpoint configs
,11-22 17:28:34.754   929  2989 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-22 17:28:34.755   929  2989 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-22 17:28:34.755   929  2989 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 17:28:34.756   929  2989 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-22 17:28:34.756   929  2989 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-22 17:28:34.757   929  2989 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 17:28:34.757   929  2989 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-22 17:28:34.757   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 17:28:34.757   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 17:28:34.757   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 17:28:34.757   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 17:28:34.757   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 17:28:34.759   929  2989 D WifiNative-HAL: Setting external_sim to 1
,11-22 17:28:34.759   929  2989 D wifi    : setting dfs flag to true, 0x7f6ecaa380
11-22 17:28:34.759  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 17:28:34.760   929  2989 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 17:28:34.760   929  2989 D wifi    : setting scan oui 0x7f6ecaa380
11-22 17:28:34.760   929  2989 D WifiHAL : Sending mac address OUI
,11-22 17:28:34.763   929  2989 E native  : do suspend false
,11-22 17:28:34.770   929  2989 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-22 17:28:34.770   929   929 D RttService: SCAN_AVAILABLE : 3
11-22 17:28:34.770   507   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-22 17:28:34.770   929  3099 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 17:28:34.771   507   926 D CommandListener: Setting iface cfg
,11-22 17:28:34.775   929  2988 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
11-22 17:28:34.775   929  2988 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 17:28:34.783   929  2988 D WifiNative-HAL: p2pGetDeviceAddress
11-22 17:28:34.784   929  2988 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 17:28:34.790   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=127532 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-22 17:28:35.696   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:36.697   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:37.699   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:37.861  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:28:37.865  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:28:37.870  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:28:37.875  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:28:37.931   929  2989 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-22 17:28:37.932   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 17:28:37.932   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 17:28:37.947   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 17:28:37.992   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 17:28:37.999  5804  5804 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 17:28:38.428  5804  5804 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 17:28:38.467  5804  5804 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 17:28:38.468  5804  5804 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 17:28:38.478   929  2989 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 17:28:38.478   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 17:28:38.479   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 17:28:38.499   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 17:28:38.514   507   926 D CommandListener: Setting iface cfg
,11-22 17:28:38.521   929  2989 D WifiStateMachine: Start Dhcp Watchdog 2
,11-22 17:28:38.531   929  5810 D DhcpClient: Receive thread started
,11-22 17:28:38.534   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-22 17:28:38.534   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-22 17:28:38.534   929  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-22 17:28:38.625   929  2989 E native  : do suspend false
,11-22 17:28:38.642   929  5809 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 17:28:38.655   929  5810 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172710, domain null
,11-22 17:28:38.656   929  5809 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172710 seconds
,11-22 17:28:38.659   929  5809 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 17:28:38.671   929  5810 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 17:28:38.672   929  5809 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 17:28:38.675   507   926 D CommandListener: Setting iface cfg
11-22 17:28:38.679   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 17:28:38.683   929  5809 D DhcpClient: Scheduling renewal in 86399s
,11-22 17:28:38.699   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-22 17:28:38.700   929  2989 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 17:28:38.700   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:38.701   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-22 17:28:38.703   929  2991 D ConnectivityService: Adding iface wlan0 to network 101
,11-22 17:28:38.712   929  2989 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 17:28:38.754   929  2991 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 17:28:38.755   929  2991 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-22 17:28:38.757   929  2991 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-22 17:28:38.759   929  2991 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-22 17:28:38.761   929  2991 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-22 17:28:38.768   929  2991 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 17:28:38.774   929  2991 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-22 17:28:38.774   929  2991 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-22 17:28:38.774   929  2991 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-22 17:28:38.774   929  2989 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 17:28:38.774   929  2991 D ConnectivityService:    accepting network in place of null
11-22 17:28:38.774   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 17:28:38.775   929  2991 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 17:28:38.790   929  5808 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131532, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 17:28:38.798   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:28:38.819   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:28:38.823  3769  3908 W QCNEJ   : |CORE| network available: 101
,11-22 17:28:38.823   929  2991 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-22 17:28:38.823   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 17:28:38.824   929  2991 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-22 17:28:38.824  3769  3908 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 17:28:38.825  3769  3908 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 17:28:38.825  3769  3908 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-22 17:28:38.826   929   946 D Tethering: MasterInitialState.processMessage what=3
11-22 17:28:38.830  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 17:28:38.830  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 17:28:38.830  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 17:28:38.830  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 17:28:38.836  5063  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 17:28:38.836  5063  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 17:28:38.836  5063  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 17:28:38.836  5063  5085 E SarControlService: no key has been found,reset the power
11-22 17:28:38.837  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 17:28:38.837  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 17:28:38.837  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 17:28:38.837  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 17:28:38.837  5088  5088 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 17:28:38.839  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 17:28:38.839  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 17:28:38.839  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 17:28:38.839  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 17:28:38.839  5088  5088 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 17:28:38.840  3991  3991 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-22 17:28:38.844  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000ec03000000000000ffffffff]
,11-22 17:28:38.845  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 17:28:38.845  3874  3874 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 17:28:38.848  5088  5102 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-22 17:28:38.848  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-22 17:28:38.848  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 17:28:38.849  3874  3874 D SystemUpdateService: onCreate
11-22 17:28:38.849  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000ed03000000000000ffffffff]
11-22 17:28:38.849  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 17:28:38.849  5088  5102 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-22 17:28:38.850  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 17:28:38.850  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 17:28:38.853  3874  3874 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 17:28:38.857   929  5807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-22 17:28:38.864  3874  3874 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 17:28:38.869  3874  5414 I iu.UploadsManager: num queued entries: 0
,11-22 17:28:38.870  3874  5414 I iu.UploadsManager: num updated entries: 0
11-22 17:28:38.870  3874  5414 I iu.SyncManager: NEXT; no task
,11-22 17:28:38.871  3874  5820 I SystemUpdateService: active receiver: enabled
,11-22 17:28:38.874  3874  3874 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 17:28:38.875  3874  3874 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-22 17:28:38.877  5759  5759 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 17:28:38.881  5759  5759 D SprintDMHelper: simOperator: 
11-22 17:28:38.881  5759  5759 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 17:28:38.902  3874  5820 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 17:28:38.912   929  5807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 16:28:38 GMT], X-Android-Received-Millis=[1479832118911], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479832118883]}
,11-22 17:28:38.912   929  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 17:28:38.913   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-22 17:28:38.913   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-22 17:28:38.914   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 17:28:38.914  3874  5820 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-22 17:28:38.914  3874  5820 I SystemUpdateService: now status is 0 (complete)
11-22 17:28:38.914  3874  5820 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 17:28:38.914  3874  5820 I SystemUpdateService: file has been verified
11-22 17:28:38.915  3874  5820 I SystemUpdateService: OTA package size = 21989297
,11-22 17:28:38.922  3874  5820 I SystemUpdateService: showing system update notification
,11-22 17:28:38.930   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 17:28:38.931  3874  3874 D SystemUpdateService: onDestroy
,11-22 17:28:38.953   929   939 D WifiService: setWifiEnabled: false pid=5635, uid=10077
,11-22 17:28:38.953   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 17:28:38.954   929  2989 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 17:28:38.954   929  2989 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-22 17:28:38.955   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 17:28:38.955   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 17:28:38.962   929  5809 D DhcpClient: Clearing IP address
,11-22 17:28:38.963   507   926 D CommandListener: Clearing all IP addresses on wlan0
,11-22 17:28:38.964   507   926 D CommandListener: Setting iface cfg
,11-22 17:28:38.965   929  5810 D DhcpClient: Receive thread stopped
,11-22 17:28:38.968  3597  5821 V NativeCrypto: SSL handshake aborted: ssl=0x7f85d85700: I/O error during system call, Connection timed out
11-22 17:28:38.974   929  3169 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-22 17:28:38.974   929  5807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-22 17:28:38.974   929  5807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-22 17:28:38.975  5015  5825 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
11-22 17:28:38.978   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 17:28:38.978   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-22 17:28:38.980   929   929 D RttService: SCAN_AVAILABLE : 1
11-22 17:28:38.980   929  3099 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 17:28:38.981   533   533 E Parcel  : Reading a NULL string not supported here.
,11-22 17:28:38.982   929  2991 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-22 17:28:38.984  3769  3908 W QCNEJ   : |CORE| network lost: 101
11-22 17:28:38.984  3769  3908 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
11-22 17:28:38.988  ,5015  5825 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
11-22 17:28:38.988  5015  5825 W Babel_NetworkConnectionCheckingService: 	... 21 more
11-22 17:28:38.989   929  5807 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-22 17:28:38.989  5015  5825 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-22 17:28:38.989   929  2989 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 17:28:38.989   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 17:28:39.005   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:28:39.024   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:28:39.024   507   926 D CommandListener: Clearing all IP addresses on wlan0
,11-22 17:28:39.024   929  2991 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-22 17:28:39.025   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 17:28:39.027   929  2989 D DhcpClient: doQuit
,11-22 17:28:39.028   929  2989 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 17:28:39.028   929   946 D Tethering: MasterInitialState.processMessage what=3
11-22 17:28:39.028   929  5809 D DhcpClient: onQuitting
11-22 17:28:39.028  5804  5804 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-22 17:28:39.030  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 17:28:39.031  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 17:28:39.031  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:39.031  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 17:28:39.033  3991  3991 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-22 17:28:39.034  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:39.036  5063  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 17:28:39.036  5063  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 17:28:39.036  5063  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 17:28:39.037  3874  3874 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 17:28:39.040  5063  5085 E SarControlService: no key has been found,reset the power
11-22 17:28:39.041  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 17:28:39.041  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 17:28:39.041  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-22 17:28:39.041  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 17:28:39.042  5088  5088 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-22 17:28:39.043  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 17:28:39.043  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 17:28:39.043  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 17:28:39.043  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 17:28:39.043  5088  5088 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 17:28:39.045  3874  3874 D SystemUpdateService: onCreate
,11-22 17:28:39.048  3874  3874 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 17:28:39.049  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000ee03000000000000ffffffff]
,11-22 17:28:39.049  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-22 17:28:39.049  5088  5102 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-22 17:28:39.049  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 17:28:39.050  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 17:28:39.050  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000ef03000000000000ffffffff]
11-22 17:28:39.050  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 17:28:39.050  5088  5102 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-22 17:28:39.050  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 17:28:39.051  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 17:28:39.051  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 17:28:39.053  5804  5804 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-22 17:28:39.055  3874  5839 I SystemUpdateService: active receiver: enabled
,11-22 17:28:39.060  3874  3874 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 17:28:39.064  3874  5414 I iu.UploadsManager: num queued entries: 0
,11-22 17:28:39.066  3874  5839 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 17:28:39.068  3874  3874 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 17:28:39.069  3874  3874 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 17:28:39.072  5759  5759 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 17:28:39.077  5759  5759 D SprintDMHelper: simOperator: 
11-22 17:28:39.077  5759  5759 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 17:28:39.077  3874  5414 I iu.UploadsManager: num updated entries: 0
,11-22 17:28:39.079   507   926 E Netd    : netlink response contains error (No such file or directory)
,11-22 17:28:39.081   929  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 17:28:39.082  5804  5804 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 17:28:39.079  3874  5839 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-22 17:28:39.086  3874  5839 I SystemUpdateService: now status is 0 (complete)
11-22 17:28:39.086  3874  5839 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 17:28:39.087  3874  5839 I SystemUpdateService: file has been verified
,11-22 17:28:39.087  3874  5839 I SystemUpdateService: OTA package size = 21989297
,11-22 17:28:39.089  3874  5414 I iu.SyncManager: NEXT; no task
,11-22 17:28:39.090  5015  5843 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 17:28:39.092  5804  5804 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 17:28:39.109  3874  5839 I SystemUpdateService: showing system update notification
,11-22 17:28:39.115   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 17:28:39.118  3874  3874 D SystemUpdateService: onDestroy
,11-22 17:28:39.196   929  2989 D wifi    : In wifi stop Hal
,11-22 17:28:39.196   929  2989 D wifi    : halHandle = 0x7f6afc3900, mVM = 0x7f8760d140, mCls = 0x2019ba
,11-22 17:28:39.197  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 17:28:39.198   929  5803 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-22 17:28:39.198   929  5803 D WifiHAL : Got a signal to exit!!!
11-22 17:28:39.198   929  5803 I WifiHAL : Exit wifi_event_loop
11-22 17:28:39.198  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:39.198   929  2989 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 17:28:39.199  4057  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 17:28:39.199   929  2989 E WifiHAL : Event processing terminated
11-22 17:28:39.199   929  2989 D wifi    : In wifi cleaned up handler
11-22 17:28:39.199   929  2989 I WifiHAL : Internal cleanup completed
,11-22 17:28:39.221   929  5803 D wifi    : set interface wlan0 flags (DOWN)
,11-22 17:28:39.221   929  2989 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 17:28:39.427   929   946 D Tethering: InitialState.processMessage what=4
,11-22 17:28:39.435   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 17:28:39.701   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:39.825   929  2991 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-22 17:28:40.702   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 17:28:43.990   929   946 I ActivityManager: Start proc 5847:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 17:28:44.079  5847  5847 D AdapterServiceConfig: Adding HeadsetService
,11-22 17:28:44.079  5847  5847 D AdapterServiceConfig: Adding A2dpService
11-22 17:28:44.079  5847  5847 D AdapterServiceConfig: Adding HidService
,11-22 17:28:44.079  5847  5847 D AdapterServiceConfig: Adding HealthService
11-22 17:28:44.079  5847  5847 D AdapterServiceConfig: Adding PanService
11-22 17:28:44.079  5847  5847 D AdapterServiceConfig: Adding GattService
11-22 17:28:44.080  5847  5847 D AdapterServiceConfig: Adding BluetoothMapService
,11-22 17:28:44.080  5847  5847 D AdapterServiceConfig: Adding SapService
,11-22 17:28:44.091   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eab0c77:true
,11-22 17:28:44.092  5847  5847 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 17:28:44.095  5847  5847 I bt_bluedroid: init
,11-22 17:28:44.095  5847  5859 I BluetoothAdapterState: Entering OffState
,11-22 17:28:44.097  5847  5860 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-22 17:28:44.097  5847  5860 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 17:28:44.097  5847  5860 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-22 17:28:44.097  5847  5860 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-22 17:28:44.097  5847  5847 I bt_bluedroid: get_profile_interface socket
,11-22 17:28:44.099  5847  5847 I bt_bluedroid: get_profile_interface sdp
,11-22 17:28:44.099  5847  5863 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-22 17:28:44.100  5847  5863 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 17:28:44.103  5847  5858 I bt_bluedroid: config_hci_snoop_log
,11-22 17:28:44.104   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 17:28:44.108  5847  5859 D BluetoothAdapterState: Current state: OFF, message: 0
11-22 17:28:44.108  5847  5859 D BluetoothAdapterProperties: Setting state to 14
11-22 17:28:44.108  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 17:28:44.110  5847  5859 D BluetoothBondStateMachine: make
,11-22 17:28:44.111  5847  5864 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 17:28:44.113  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
,11-22 17:28:44.115  5847  5847 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 17:28:44.116  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:28:44.117  5847  5847 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 17:28:44.118  5847  5847 D BtGatt.GattService: Received start request. Starting profile...
,11-22 17:28:44.118  5847  5847 D BtGatt.GattService: start()
11-22 17:28:44.118  5847  5847 I bt_bluedroid: get_profile_interface gatt
,11-22 17:28:44.119  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:28:44.119  5847  5847 D BtGatt.AdvertiseManager: advertise manager created
,11-22 17:28:44.124  5847  5847 V BluetoothAdapterState: isTurningOff()=false
,11-22 17:28:44.124  5847  5847 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:44.124  5847  5847 V BluetoothAdapterState: isBleTurningOn()=true
11-22 17:28:44.124  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:44.125  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 17:28:44.126  5847  5859 I bt_bluedroid: bt_bluedroid
,11-22 17:28:44.126  5847  5860 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-22 17:28:44.127  5847  5860 I bt_hci  : start_up
,11-22 17:28:44.131  5847  5860 I bt_vendor: alloc value 0xf413d871
11-22 17:28:44.131  5847  5860 I bt_vendor: init
,11-22 17:28:44.132  5847  5860 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 17:28:44.132  5847  5860 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 17:28:44.241  5847  5860 D bt_hci  : start_up starting async portion
,11-22 17:28:44.242  5847  5867 I bt_hci  : event_finish_startup
11-22 17:28:44.242  5847  5867 I bt_hci_h4: hal_open
11-22 17:28:44.242  5847  5867 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 17:28:44.238  5868  5868 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 17:28:44.246  5847  5867 I bt_userial_vendor: device fd = 54 open
,11-22 17:28:44.260  5847  5867 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 17:28:44.263  5847  5867 D bt_hwcfg: Chipset BCM4358A3
,11-22 17:28:44.263  5847  5867 D bt_hwcfg: Target name = [BCM4358A3]
11-22 17:28:44.263  5847  5867 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 17:28:44.669  5847  5867 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 17:28:44.670  5847  5867 D bt_hwcfg: Settlement delay -- 100 ms
,11-22 17:28:44.670  5847  5867 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 17:28:44.806  5847  5867 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 17:28:44.806  5847  5867 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-22 17:28:44.807  5847  5867 I bt_hwcfg: vendor lib fwcfg completed
11-22 17:28:44.808  5847  5867 I bt_vendor: firmware callback
11-22 17:28:44.808  5847  5867 I bt_hci  : firmware_config_callback
,11-22 17:28:44.818  5847  5870 I bt_btu  : btu_task pending for preload complete event
,11-22 17:28:44.819  5847  5870 I bt_btu_task: Bluetooth chip preload is complete
11-22 17:28:44.819  5847  5870 I bt_btu  : btu_task received preload complete event
,11-22 17:28:44.825  5847  5870 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 17:28:44.825  5847  5870 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 17:28:44.825  5847  5870 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_AVDT
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_BTM
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_SDP
11-22 17:28:44.826  5847  5870 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 17:28:44.827  5847  5870 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 17:28:44.827  5847  5870 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 17:28:44.827  5847  5870 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 17:28:44.909  5847  5870 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40bb549
11-22 17:28:44.910  5847  5870 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40bb549 
,11-22 17:28:44.931  5847  5863 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 17:28:44.932  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 17:28:44.933  5847  5863 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 17:28:44.936  5847  5863 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 17:28:44.939  5847  5863 D BluetoothAdapterProperties: Scan Mode:20
,11-22 17:28:44.939  5847  5863 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 17:28:44.939  5847  5863 D bt_hci  : do_postload posting postload work item
11-22 17:28:44.939  5847  5867 I bt_hci  : event_postload
11-22 17:28:44.939  5847  5867 I bt_vendor: sco_config_cb
11-22 17:28:44.939  5847  5867 I bt_hci  : sco_config_callback postload finished.
11-22 17:28:44.943  5847  5863 D bt_bte_conf: Device ID record 1 : primary
11-22 17:28:44.943  5847  5863 D bt_bte_conf:   vendorId            = 000f
11-22 17:28:44.943  5847  5863 D bt_bte_conf:   vendorIdSource      = 0001
,11-22 17:28:44.943  5847  5863 D bt_bte_conf:   product             = 1200
11-22 17:28:44.943  5847  5863 D bt_bte_conf:   version             = 1436
11-22 17:28:44.943  5847  5863 D bt_bte_conf:   clientExecutableURL = 
11-22 17:28:44.943  5847  5863 D bt_bte_conf:   serviceDescription  = 
11-22 17:28:44.943  5847  5863 D bt_bte_conf:   documentationURL    = 
11-22 17:28:44.943  5847  5863 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 17:28:44.944  5847  5860 D bt_stack_manager: event_start_up_stack finished
,11-22 17:28:44.947  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:44.948  5847  5867 I bt_vendor: low_power_mode_cb
,11-22 17:28:44.949  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-22 17:28:44.949  5847  5859 D BluetoothAdapterProperties: Setting state to 15
11-22 17:28:44.949  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 17:28:44.950  5847  5859 I BluetoothAdapterState: Entering BleOnState
,11-22 17:28:44.956  5847  5859 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-22 17:28:44.956  5847  5859 D BluetoothAdapterProperties: Setting state to 11
11-22 17:28:44.956  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 17:28:44.960  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:28:44.963  5847  5847 D HeadsetService: Received start request. Starting profile...
11-22 17:28:44.964  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:44.965  5847  5847 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 17:28:44.966  5847  5847 D HeadsetStateMachine: make
,11-22 17:28:44.976  5847  5847 D HeadsetStateMachine: max_hf_connections = 1
,11-22 17:28:44.976  5847  5847 I bt_bluedroid: get_profile_interface handsfree
11-22 17:28:44.977  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 17:28:44.977  5847  5863 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-22 17:28:44.978  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
,11-22 17:28:44.980  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:28:44.981  5847  5847 D A2dpService: Received start request. Starting profile...
,11-22 17:28:44.981  5847  5847 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 17:28:44.982  5847  5847 I bt_bluedroid: get_profile_interface avrcp
,11-22 17:28:44.987  5847  5847 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 17:28:44.988  5847  5847 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 17:28:44.988  5847  5847 D A2dpStateMachine: make
,11-22 17:28:44.989  5847  5847 I bt_bluedroid: get_profile_interface a2dp
11-22 17:28:44.990  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-22 17:28:44.991  5847  5878 D A2dpStateMachine: Enter Disconnected: -2
11-22 17:28:44.993  5847  5847 I BluetoothHidServiceJni: classInitNative: succeeds
11-22 17:28:44.994  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:28:44.994  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 17:28:44.995  5693  5693 D BluetoothInputDevice: Proxy object connected
,11-22 17:28:44.996  5693  5693 D HidProfile: Bluetooth service connected
11-22 17:28:44.998  5847  5847 D HidService: Received start request. Starting profile...
11-22 17:28:44.999  5847  5847 I bt_bluedroid: get_profile_interface hidhost
11-22 17:28:44.999  5847  5863 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf409c56d
11-22 17:28:44.999  5847  5847 D HidService: setHidService(): set to: null
11-22 17:28:44.999  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 17:28:44.999  5847  5847 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 17:28:45.000  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:28:45.000  5847  5847 D HealthService: Received start request. Starting profile...
,11-22 17:28:45.002  5847  5847 I bt_bluedroid: get_profile_interface health
11-22 17:28:45.004  5847  5847 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 17:28:45.005  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:28:45.006  5847  5847 D PanService: Received start request. Starting profile...
,11-22 17:28:45.006  5847  5847 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 17:28:45.007  5847  5847 I bt_bluedroid: get_profile_interface pan
11-22 17:28:45.007  5693  5693 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 17:28:45.007  5847  5863 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-22 17:28:45.007  5693  5693 D PanProfile: Bluetooth service connected
11-22 17:28:45.009  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:28:45.010  5693  5693 D BluetoothMap: Proxy object connected
,11-22 17:28:45.010  5847  5847 D BluetoothMapService: Received start request. Starting profile...
11-22 17:28:45.011  5847  5847 D BluetoothMapService: start()
11-22 17:28:45.011  5693  5693 D MapProfile: Bluetooth service connected
11-22 17:28:45.011  5693  5693 D BluetoothMap: getConnectedDevices()
,11-22 17:28:45.012  5693  5693 D BluetoothMap: Bluetooth is Not enabled
,11-22 17:28:45.013  5847  5847 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 17:28:45.014  5847  5847 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-22 17:28:45.014  5847  5847 D BluetoothMapAppObserver: createReceiver()
11-22 17:28:45.015  5847  5847 D BluetoothMapAppObserver: initObservers()
11-22 17:28:45.015  5847  5847 D BluetoothMapAppObserver: getEnabledAccountItems()
11-22 17:28:45.021  5847  5847 V SapService: SapBinder()
11-22 17:28:45.021  5847  5847 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:28:45.021  5847  5847 D SapService: Received start request. Starting profile...
,11-22 17:28:45.021  5847  5847 V SapService: start()
11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isTurningOn()=true
11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:45.023  5847  5876 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isTurningOn()=true
11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 17:28:45.023  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOn()=true
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOn()=true
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOn()=true
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isTurningOn()=true
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:45.024  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:45.025  5847  5847 V BluetoothAdapterState: isTurningOff()=false
,11-22 17:28:45.025  5847  5847 V BluetoothAdapterState: isTurningOn()=true
11-22 17:28:45.025  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:45.025  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:45.025  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 17:28:45.026  5847  5859 D BluetoothAdapterProperties: ScanMode =  20
11-22 17:28:45.026  5847  5859 D BluetoothAdapterProperties: State =  11
,11-22 17:28:45.027  5847  5863 D BluetoothAdapterProperties: Scan Mode:21
11-22 17:28:45.027  5847  5863 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 17:28:45.027  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-22 17:28:45.028  5847  5859 D BluetoothAdapterProperties: Setting state to 12
,11-22 17:28:45.028  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 17:28:45.028  5847  5859 I BluetoothAdapterState: Entering OnState
11-22 17:28:45.029  3146  3158 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 17:28:45.031  3146  3146 D BluetoothA2dp: Proxy object connected
11-22 17:28:45.031  5693  5704 D BluetoothPbap: onBluetoothStateChange: up=true
,11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 17:28:45.032  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 17:28:45.033  3146  3159 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:28:45.033  5693  5705 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 17:28:45.034  5693  5704 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 17:28:45.034   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 17:28:45.034  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 17:28:45.034   929   929 D BluetoothA2dp: Proxy object connected
11-22 17:28:45.034  3146  4009 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 17:28:45.036  3146  3146 D BluetoothInputDevice: Proxy object connected
,11-22 17:28:45.036  3797  3818 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:28:45.036  3146  3146 D HidProfile: Bluetooth service connected
11-22 17:28:45.036   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:28:45.036  5693  5705 D BluetoothPan: onBluetoothStateChange on: true
11-22 17:28:45.037   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 17:28:45.037  3146  3361 D BluetoothMap: onBluetoothStateChange: up=true
11-22 17:28:45.038   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:28:45.038  3146  3146 D BluetoothMap: Proxy object connected
11-22 17:28:45.038  3146  3146 D MapProfile: Bluetooth service connected
11-22 17:28:45.038  3146  3146 D BluetoothMap: getConnectedDevices()
11-22 17:28:45.038  3146  4009 D BluetoothPan: onBluetoothStateChange on: true
,11-22 17:28:45.040  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 17:28:45.040  3146  3146 D PanProfile: Bluetooth service connected
11-22 17:28:45.040  5847  5847 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 17:28:45.041  5847  5847 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-22 17:28:45.042  3146  3361 D BluetoothPbap: onBluetoothStateChange: up=true
,11-22 17:28:45.043  5847  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:28:45.045  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-22 17:28:45.046   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 17:28:45.046  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:45.047  5847  5847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:28:45.048  5693  5693 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-22 17:28:45.048  5847  5847 D ObexServerSockets: Succeed to create listening sockets 
11-22 17:28:45.049  5847  5847 D ObexServerSockets0: startAccept()
11-22 17:28:45.049  5847  5847 D ObexServerSockets0: prepareForNewConnect()
,11-22 17:28:45.051  5847  5847 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-22 17:28:45.051  5847  5847 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-22 17:28:45.051  5847  5884 D ObexServerSockets0: Accepting socket connection...
11-22 17:28:45.051  5847  5847 D BluetoothMapService: onReceive
11-22 17:28:45.051  5847  5847 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 17:28:45.052  5847  5847 D BluetoothMapService: STATE_ON
11-22 17:28:45.052  5847  5885 D ObexServerSockets0: Accepting socket connection...
11-22 17:28:45.052  5693  5693 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-22 17:28:45.054  5847  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:28:45.055  5847  5886 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-22 17:28:45.055  5847  5886 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 17:28:45.059  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 17:28:45.061  5693  5693 D BluetoothA2dp: Proxy object connected
,11-22 17:28:45.067  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 17:28:45.068  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,11-22 17:28:45.074  3146  3146 D BluetoothPbap: Proxy object connected
,11-22 17:28:45.074  5693  5693 D BluetoothPbap: Proxy object connected
11-22 17:28:45.074  3146  3146 D PbapServerProfile: Bluetooth service connected
11-22 17:28:45.075  5693  5693 D PbapServerProfile: Bluetooth service connected
,11-22 17:28:45.079  5847  5847 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 17:28:45.079  5847  5847 D ObexServerSockets0: prepareForNewConnect()
,11-22 17:28:45.083  5847  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:28:45.098  5847  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:28:45.099  5847  5894 I BtOppRfcommListener: Accept thread started.
,11-22 17:28:45.135   929   929 D BluetoothHeadset: Proxy object connected
11-22 17:28:45.135   929   929 D BluetoothHeadset: Proxy object connected
11-22 17:28:45.135  3146  3159 D BluetoothHeadset: Proxy object connected
11-22 17:28:45.136  3146  3146 D HeadsetProfile: Bluetooth service connected
11-22 17:28:45.136  3797  3996 D BluetoothHeadset: Proxy object connected
,11-22 17:28:45.137   929   929 D BluetoothHeadset: Proxy object connected
,11-22 17:28:45.137  3797  3812 D BluetoothHeadset: Proxy object connected
11-22 17:28:45.137   929   946 D BluetoothHeadset: Proxy object connected
11-22 17:28:45.137   929   946 D BluetoothHeadset: Proxy object connected
11-22 17:28:45.139   929   946 D BluetoothHeadset: Proxy object connected
,11-22 17:28:45.155  5693  5705 D BluetoothHeadset: Proxy object connected
,11-22 17:28:45.157  5693  5693 D HeadsetProfile: Bluetooth service connected
,11-22 17:28:46.781   929  2991 D ConnectivityService: handlePromptUnvalidated 101
,11-22 17:28:46.929  3677  3865 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-22 17:28:46.929  3677  3865 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-22 17:28:46.957  3597  3597 I ConfigService: onCreate
,11-22 17:28:48.969  5847  5859 D BluetoothAdapterState: Current state: ON, message: 23
11-22 17:28:48.970  5847  5859 D BluetoothAdapterProperties: Setting state to 13
11-22 17:28:48.970  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-22 17:28:48.971  5847  5859 D BluetoothAdapterProperties: onBluetoothDisable()
,11-22 17:28:48.973  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
,11-22 17:28:48.979  5847  5847 D BluetoothMapService: onReceive
11-22 17:28:48.979  5847  5847 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 17:28:48.979  5847  5847 D BluetoothMapService: STATE_TURNING_OFF
,11-22 17:28:48.980  5847  5847 D BluetoothMapService: MAP Service closeService in
11-22 17:28:48.980  5847  5847 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 17:28:48.980  5847  5847 D ObexServerSockets0: shutdown(block = true)
11-22 17:28:48.982  5847  5847 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 17:28:48.982  5847  5872 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-22 17:28:48.982  5847  5847 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 17:28:48.982  5847  5884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-22 17:28:48.983  5847  5885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 17:28:48.985  5847  5847 I BtOppRfcommListener: stopping Accept Thread
11-22 17:28:48.985  5847  5894 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 17:28:48.986  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 17:28:48.987  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 17:28:48.989  5847  5863 D BluetoothAdapterProperties: Scan Mode:20
11-22 17:28:48.989  5847  5894 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-22 17:28:48.990  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 17:28:48.991  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 17:28:48.991  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 17:28:48.993  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 17:28:48.994  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:48.996  5847  5847 D HeadsetService: Received stop request...Stopping profile...
,11-22 17:28:48.999   929   929 D BluetoothHeadset: Proxy object disconnected
,11-22 17:28:49.002  5693  5705 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:49.002   929   929 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:49.003  3146  3159 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:49.003  3797  3818 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:49.004   929   929 D BluetoothHeadset: Proxy object disconnected
11-22 17:28:49.004  5847  5847 D A2dpService: Received stop request...Stopping profile...
11-22 17:28:49.005  5847  5878 D A2dpStateMachine: Exit Disconnected: -1
11-22 17:28:49.006  5693  5693 D DockEventReceiver: finishStartingService: stopping service
11-22 17:28:49.006   929   929 D BluetoothA2dp: Proxy object disconnected
11-22 17:28:49.007  5847  5847 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:49.007  5847  5847 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:49.007  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:49.007  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:49.007  5693  5693 D HeadsetProfile: Bluetooth service disconnected
11-22 17:28:49.008  5693  5693 D BluetoothA2dp: Proxy object disconnected
11-22 17:28:49.010  3146  3146 D HeadsetProfile: Bluetooth service disconnected
11-22 17:28:49.010  3146  3146 D BluetoothA2dp: Proxy object disconnected
11-22 17:28:49.013  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 17:28:49.013  5847  5847 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 17:28:49.013  5847  5847 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-22 17:28:49.013  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:49.014  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:49.014  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 17:28:49.014  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 17:28:49.014  5847  5847 D HidService: Received stop request...Stopping profile...
11-22 17:28:49.014  5847  5863 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 17:28:49.015  5847  5847 D HidService: Stopping Bluetooth HidService
11-22 17:28:49.016  3146  3146 D BluetoothInputDevice: Proxy object disconnected
,11-22 17:28:49.017  3146  3146 D HidProfile: Bluetooth service disconnected
,11-22 17:28:49.017  5847  5847 D HealthService: Received stop request...Stopping profile...
,11-22 17:28:49.019  5693  5693 D BluetoothInputDevice: Proxy object disconnected
11-22 17:28:49.019  5693  5693 D HidProfile: Bluetooth service disconnected
11-22 17:28:49.019  5847  5847 D PanService: Received stop request...Stopping profile...
,11-22 17:28:49.020  5693  5693 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 17:28:49.020  5693  5693 D PanProfile: Bluetooth service disconnected
11-22 17:28:49.021  3146  3146 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 17:28:49.021  3146  3146 D PanProfile: Bluetooth service disconnected
,11-22 17:28:49.023  5847  5847 D BluetoothMapService: Received stop request...Stopping profile...
11-22 17:28:49.024  5847  5847 D BluetoothMapService: stop()
,11-22 17:28:49.024  5847  5847 D BluetoothMapAppObserver: deinitObservers()
,11-22 17:28:49.024  5847  5847 D BluetoothMapAppObserver: removeReceiver()
11-22 17:28:49.026  5693  5693 D BluetoothMap: Proxy object disconnected
11-22 17:28:49.026  5693  5693 D MapProfile: Bluetooth service disconnected
11-22 17:28:49.026  3146  3146 D BluetoothMap: Proxy object disconnected
11-22 17:28:49.026  5847  5847 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:49.026  3146  3146 D MapProfile: Bluetooth service disconnected
11-22 17:28:49.026  5847  5847 V BluetoothAdapterState: isTurningOn()=false
,11-22 17:28:49.026  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:49.026  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:49.026  5847  5847 D SapService: Received stop request...Stopping profile...
11-22 17:28:49.026  5847  5847 V SapService: stop()
11-22 17:28:49.028  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 17:28:49.028  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:49.028  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 17:28:49.028  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 17:28:49.028  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 17:28:49.028  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 17:28:49.029  5847  5870 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:49.030  3146  3146 D BluetoothPbap: Proxy object disconnected
11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 17:28:49.030  3146  3146 D PbapServerProfile: Bluetooth service disconnected
11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:49.030  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:49.031  5847  5847 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-22 17:28:49.031  5847  5847 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 17:28:49.031  5847  5863 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 17:28:49.031  5847  5847 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 17:28:49.031  5847  5863 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 17:28:49.032  5847  5847 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 17:28:49.032  5847  5847 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:49.032  5847  5847 V BluetoothAdapterState: isTurningOn()=false
,11-22 17:28:49.032  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:49.032  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:49.032  5847  5847 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 17:28:49.032  5847  5847 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-22 17:28:49.033  5847  5847 D BluetoothMapService: MAP Service closeService in
11-22 17:28:49.033  5847  5847 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:49.033  5847  5847 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:49.033  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:49.033  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:49.033  5847  5847 D BluetoothMapService: cleanup()
11-22 17:28:49.033  5847  5847 D BluetoothMapService: MAP Service closeService in
11-22 17:28:49.034  5847  5847 V BluetoothAdapterState: isTurningOff()=true
11-22 17:28:49.034  5847  5847 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:49.034  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 17:28:49.034  5847  5847 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:49.034  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 17:28:49.034  5847  5859 D BluetoothAdapterProperties: Setting state to 15
11-22 17:28:49.034  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 17:28:49.034  5847  5859 I BluetoothAdapterState: Entering BleOnState
11-22 17:28:49.035  3146  3159 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 17:28:49.036  5693  5704 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 17:28:49.037  3146  3158 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:49.038  5693  5705 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-22 17:28:49.038  5693  5704 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:49.039  5693  5705 D BluetoothMap: onBluetoothStateChange: up=false
11-22 17:28:49.039   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 17:28:49.039  3146  4009 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 17:28:49.040  3797  3996 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 17:28:49.040   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:49.040  5693  5704 D BluetoothPan: onBluetoothStateChange on: false
11-22 17:28:49.041   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:49.041  3146  3361 D BluetoothMap: onBluetoothStateChange: up=false
11-22 17:28:49.042   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 17:28:49.042  5693  5705 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 17:28:49.042  3146  3159 D BluetoothPan: onBluetoothStateChange on: false
11-22 17:28:49.043  3146  3158 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 17:28:49.044  5847  5859 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-22 17:28:49.044  5847  5859 D BluetoothAdapterProperties: Setting state to 16
11-22 17:28:49.044  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 17:28:49.044  5693  5693 D BluetoothPbap: Proxy object disconnected
11-22 17:28:49.044  5693  5693 D PbapServerProfile: Bluetooth service disconnected
11-22 17:28:49.044  5847  5859 D BluetoothAdapterProperties: onBleDisable
11-22 17:28:49.045  5847  5859 I BluetoothAdapterState: Entering PendingCommandState
11-22 17:28:49.045  5847  5860 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 17:28:49.045  5847  5863 D BluetoothAdapterProperties: Scan Mode:20
11-22 17:28:49.047  5847  5870 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 17:28:49.047  5847  5870 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 17:28:49.047  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 17:28:49.048  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 17:28:49.049  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:49.054  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,11-22 17:28:49.056  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 17:28:49.263  5847  5863 I bt_hci  : shut_down
,11-22 17:28:49.273  5847  5867 D bt_hwcfg: hw_epilog_process
,11-22 17:28:49.274  5847  5867 I bt_vendor: low_power_mode_cb
,11-22 17:28:49.277  5847  5867 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 17:28:49.277  5847  5867 I bt_vendor: epilog_cb
,11-22 17:28:49.277  5847  5867 I bt_hci  : epilog_finished_callback
,11-22 17:28:49.283  5847  5863 I bt_hci_h4: hal_close
,11-22 17:28:49.284  5847  5863 I bt_userial_vendor: device fd = 54 close
,11-22 17:28:49.404  5847  5860 D bt_stack_manager: event_shut_down_stack finished.
,11-22 17:28:49.405  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 17:28:49.410  5847  5847 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 17:28:49.410  5847  5859 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-22 17:28:49.411  5847  5847 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 17:28:49.411  5847  5847 D BtGatt.GattService: stop()
,11-22 17:28:49.412  5847  5847 D BtGatt.AdvertiseManager: advertise clients cleared
,11-22 17:28:49.415  5847  5847 V BluetoothAdapterState: isTurningOff()=false
,11-22 17:28:49.416  5847  5847 V BluetoothAdapterState: isTurningOn()=false
11-22 17:28:49.416  5847  5847 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:28:49.416  5847  5847 V BluetoothAdapterState: isBleTurningOff()=true
11-22 17:28:49.417  5847  5859 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 17:28:49.417  5847  5859 D BluetoothAdapterProperties: Setting state to 10
11-22 17:28:49.417  5847  5859 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-22 17:28:49.420  5847  5859 I BluetoothAdapterState: Entering OffState
,11-22 17:28:49.422   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 17:28:49.434  5847  5847 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 17:28:49.434  5847  5847 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 17:28:49.434  5847  5847 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-22 17:28:49.437  5847  5860 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 17:28:49.445  5847  5847 I art     : System.exit called, status: 0
,11-22 17:28:49.445  5847  5847 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 17:28:49.470   929   940 I ActivityManager: Process com.android.bluetooth (pid 5847) has died
,11-22 17:28:50.703   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:51.703   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:51.984  3597  3597 I ConfigService: onDestroy
,11-22 17:28:52.705   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:53.705   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:53.967  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:53.967  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 17:28:53.972  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:53.972  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dfe1e removed from the list
11-22 17:28:53.972  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:28:53.975  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:28:53.975  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdb15 added. We now have 4 listener(s)
11-22 17:28:53.975  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 17:28:53.977  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:28:53.977  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdb15 removed from the list
,11-22 17:28:53.977  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:28:53.979  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:28:53.980  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@777de2a added. We now have 4 listener(s)
11-22 17:28:53.980  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 17:28:54.706   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:28:55.707   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 17:28:58.992  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:28:59.030   929   946 I ActivityManager: Start proc 5903:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 17:28:59.122  5903  5903 D AdapterServiceConfig: Adding HeadsetService
,11-22 17:28:59.123  5903  5903 D AdapterServiceConfig: Adding A2dpService
11-22 17:28:59.123  5903  5903 D AdapterServiceConfig: Adding HidService
,11-22 17:28:59.123  5903  5903 D AdapterServiceConfig: Adding HealthService
11-22 17:28:59.123  5903  5903 D AdapterServiceConfig: Adding PanService
,11-22 17:28:59.123  5903  5903 D AdapterServiceConfig: Adding GattService
11-22 17:28:59.123  5903  5903 D AdapterServiceConfig: Adding BluetoothMapService
11-22 17:28:59.124  5903  5903 D AdapterServiceConfig: Adding SapService
,11-22 17:28:59.135   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1870d3:true
,11-22 17:28:59.135  5903  5903 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 17:28:59.138  5903  5903 I bt_bluedroid: init
,11-22 17:28:59.139  5903  5915 I BluetoothAdapterState: Entering OffState
,11-22 17:28:59.140  5903  5916 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-22 17:28:59.141  5903  5916 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 17:28:59.141  5903  5916 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-22 17:28:59.141  5903  5916 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-22 17:28:59.142  5903  5903 I bt_bluedroid: get_profile_interface socket
,11-22 17:28:59.143  5903  5919 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 17:28:59.144  5903  5903 I bt_bluedroid: get_profile_interface sdp
11-22 17:28:59.145  5903  5919 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 17:28:59.149  5903  5914 I bt_bluedroid: config_hci_snoop_log
11-22 17:28:59.150   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 17:28:59.154  5903  5915 D BluetoothAdapterState: Current state: OFF, message: 0
11-22 17:28:59.154  5903  5915 D BluetoothAdapterProperties: Setting state to 14
,11-22 17:28:59.154  5903  5915 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 17:28:59.156  5903  5915 D BluetoothBondStateMachine: make
,11-22 17:28:59.157  5903  5920 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 17:28:59.160  5903  5915 I BluetoothAdapterState: Entering PendingCommandState
,11-22 17:28:59.161  5903  5903 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-22 17:28:59.164  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:28:59.164  5903  5903 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 17:28:59.165  5903  5903 D BtGatt.GattService: Received start request. Starting profile...
11-22 17:28:59.165  5903  5903 D BtGatt.GattService: start()
,11-22 17:28:59.165  5903  5903 I bt_bluedroid: get_profile_interface gatt
,11-22 17:28:59.166  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:28:59.166  5903  5903 D BtGatt.AdvertiseManager: advertise manager created
,11-22 17:28:59.171  5903  5903 V BluetoothAdapterState: isTurningOff()=false
11-22 17:28:59.171  5903  5903 V BluetoothAdapterState: isTurningOn()=false
,11-22 17:28:59.171  5903  5903 V BluetoothAdapterState: isBleTurningOn()=true
11-22 17:28:59.171  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:28:59.171  5903  5915 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 17:28:59.172  5903  5915 I bt_bluedroid: bt_bluedroid
11-22 17:28:59.172  5903  5916 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-22 17:28:59.172  5903  5916 I bt_hci  : start_up
,11-22 17:28:59.177  5903  5916 I bt_vendor: alloc value 0xf413d871
11-22 17:28:59.177  5903  5916 I bt_vendor: init
11-22 17:28:59.177  5903  5916 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,11-22 17:28:59.177  5903  5916 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 17:28:59.285  5903  5916 D bt_hci  : start_up starting async portion
11-22 17:28:59.286  5903  5923 I bt_hci  : event_finish_startup
11-22 17:28:59.286  5903  5923 I bt_hci_h4: hal_open
11-22 17:28:59.286  5903  5923 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 17:28:59.285  5924  5924 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-22 17:28:59.289  5903  5923 I bt_userial_vendor: device fd = 54 open
,11-22 17:28:59.304  5903  5923 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 17:28:59.307  5903  5923 D bt_hwcfg: Chipset BCM4358A3
,11-22 17:28:59.307  5903  5923 D bt_hwcfg: Target name = [BCM4358A3]
11-22 17:28:59.307  5903  5923 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 17:28:59.820  5903  5923 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-22 17:28:59.820  5903  5923 D bt_hwcfg: Settlement delay -- 100 ms
,11-22 17:28:59.820  5903  5923 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 17:28:59.954  5903  5923 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 17:28:59.955  5903  5923 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-22 17:28:59.956  5903  5923 I bt_hwcfg: vendor lib fwcfg completed
,11-22 17:28:59.957  5903  5923 I bt_vendor: firmware callback
11-22 17:28:59.957  5903  5923 I bt_hci  : firmware_config_callback
,11-22 17:28:59.967  5903  5926 I bt_btu  : btu_task pending for preload complete event
,11-22 17:28:59.967  5903  5926 I bt_btu_task: Bluetooth chip preload is complete
11-22 17:28:59.967  5903  5926 I bt_btu  : btu_task received preload complete event
,11-22 17:28:59.974  5903  5926 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 17:28:59.974  5903  5926 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-22 17:28:59.974  5903  5926 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-22 17:28:59.974  5903  5926 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-22 17:28:59.975  5903  5926 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 17:28:59.975  5903  5926 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 17:28:59.975  5903  5926 I         : BTE_InitTraceLevels -- TRC_BNEP
11-22 17:28:59.975  5903  5926 I         : BTE_InitTraceLevels -- TRC_BTM
,11-22 17:28:59.976  5903  5926 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 17:28:59.976  5903  5926 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 17:28:59.976  5903  5926 I         : BTE_InitTraceLevels -- TRC_SDP
,11-22 17:28:59.976  5903  5926 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 17:28:59.976  5903  5926 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 17:28:59.976  5903  5926 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 17:28:59.976  5903  5926 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 17:29:00.063  5903  5926 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40bb549
11-22 17:29:00.063  5903  5926 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40bb549 
,11-22 17:29:00.074  5903  5919 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 17:29:00.076  5903  5919 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 17:29:00.076  5903  5919 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-22 17:29:00.077  5903  5919 D BluetoothAdapterProperties: Name is: Nexus 6P
11-22 17:29:00.077  5903  5919 D BluetoothAdapterProperties: Scan Mode:20
11-22 17:29:00.078  5903  5919 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 17:29:00.078  5903  5919 D bt_hci  : do_postload posting postload work item
11-22 17:29:00.078  5903  5923 I bt_hci  : event_postload
11-22 17:29:00.078  5903  5923 I bt_vendor: sco_config_cb
11-22 17:29:00.078  5903  5923 I bt_hci  : sco_config_callback postload finished.
,11-22 17:29:00.080  5903  5919 D bt_bte_conf: Device ID record 1 : primary
11-22 17:29:00.080  5903  5919 D bt_bte_conf:   vendorId            = 000f
11-22 17:29:00.080  5903  5919 D bt_bte_conf:   vendorIdSource      = 0001
11-22 17:29:00.080  5903  5919 D bt_bte_conf:   product             = 1200
11-22 17:29:00.080  5903  5919 D bt_bte_conf:   version             = 1436
11-22 17:29:00.080  5903  5919 D bt_bte_conf:   clientExecutableURL = 
11-22 17:29:00.080  5903  5919 D bt_bte_conf:   serviceDescription  = 
,11-22 17:29:00.080  5903  5919 D bt_bte_conf:   documentationURL    = 
11-22 17:29:00.081  5903  5919 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 17:29:00.081  5903  5916 D bt_stack_manager: event_start_up_stack finished
,11-22 17:29:00.081  5903  5915 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 17:29:00.082  5903  5915 D BluetoothAdapterProperties: Setting state to 15
11-22 17:29:00.082  5903  5915 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 17:29:00.082  5903  5915 I BluetoothAdapterState: Entering BleOnState
11-22 17:29:00.084  5903  5915 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 17:29:00.084  5903  5915 D BluetoothAdapterProperties: Setting state to 11
11-22 17:29:00.085  5903  5915 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 17:29:00.089  5903  5923 I bt_vendor: low_power_mode_cb
,11-22 17:29:00.092  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:29:00.094  5903  5903 D HeadsetService: Received start request. Starting profile...
11-22 17:29:00.096  5903  5903 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 17:29:00.097  5903  5903 D HeadsetStateMachine: make
,11-22 17:29:00.101  5903  5915 I BluetoothAdapterState: Entering PendingCommandState
,11-22 17:29:00.106  5903  5903 D HeadsetStateMachine: max_hf_connections = 1
11-22 17:29:00.106  5903  5903 I bt_bluedroid: get_profile_interface handsfree
11-22 17:29:00.107  5903  5919 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 17:29:00.107  5903  5919 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-22 17:29:00.111  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:29:00.111  5903  5903 D A2dpService: Received start request. Starting profile...
11-22 17:29:00.112  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 17:29:00.112  5903  5903 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 17:29:00.113  5903  5903 I bt_bluedroid: get_profile_interface avrcp
,11-22 17:29:00.119  5903  5903 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 17:29:00.119  5903  5903 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 17:29:00.119  5903  5903 D A2dpStateMachine: make
,11-22 17:29:00.121  5903  5903 I bt_bluedroid: get_profile_interface a2dp
,11-22 17:29:00.123  5903  5919 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 17:29:00.124  5903  5933 D A2dpStateMachine: Enter Disconnected: -2
,11-22 17:29:00.124  5903  5903 I BluetoothHidServiceJni: classInitNative: succeeds
,11-22 17:29:00.126  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:29:00.127  5903  5903 D HidService: Received start request. Starting profile...
,11-22 17:29:00.127  5903  5903 I bt_bluedroid: get_profile_interface hidhost
11-22 17:29:00.127  5903  5903 D HidService: setHidService(): set to: null
11-22 17:29:00.127  5903  5919 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf409c56d
11-22 17:29:00.127  5903  5919 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 17:29:00.128  5903  5903 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-22 17:29:00.128  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:29:00.129  5903  5903 D HealthService: Received start request. Starting profile...
,11-22 17:29:00.130  5903  5903 I bt_bluedroid: get_profile_interface health
11-22 17:29:00.131  5903  5903 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 17:29:00.132  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:29:00.132  5903  5903 D PanService: Received start request. Starting profile...
,11-22 17:29:00.132  5903  5903 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 17:29:00.132  5903  5903 I bt_bluedroid: get_profile_interface pan
11-22 17:29:00.133  5903  5919 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 17:29:00.134  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:29:00.135  5903  5903 D BluetoothMapService: Received start request. Starting profile...
11-22 17:29:00.135  5903  5903 D BluetoothMapService: start()
,11-22 17:29:00.137  5903  5903 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 17:29:00.138  5903  5903 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-22 17:29:00.138  5903  5903 D BluetoothMapAppObserver: createReceiver()
11-22 17:29:00.139  5903  5903 D BluetoothMapAppObserver: initObservers()
11-22 17:29:00.139  5903  5903 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 17:29:00.145  5903  5903 V SapService: SapBinder()
,11-22 17:29:00.145  5903  5903 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
11-22 17:29:00.145  5903  5903 D SapService: Received start request. Starting profile...
11-22 17:29:00.145  5903  5903 V SapService: start()
,11-22 17:29:00.148  5903  5903 V BluetoothAdapterState: isTurningOff()=false
,11-22 17:29:00.149  5903  5903 V BluetoothAdapterState: isTurningOn()=true
11-22 17:29:00.149  5903  5903 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:29:00.149  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:29:00.149  5903  5931 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 17:29:00.149  5903  5903 V BluetoothAdapterState: isTurningOff()=false
,11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isTurningOn()=true
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isTurningOff()=false
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isTurningOn()=true
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isTurningOff()=false
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isTurningOn()=true
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:29:00.150  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isTurningOff()=false
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isTurningOn()=true
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isTurningOff()=false
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isTurningOn()=true
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:29:00.151  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
11-22 17:29:00.152  5903  5903 V BluetoothAdapterState: isTurningOff()=false
11-22 17:29:00.152  5903  5903 V BluetoothAdapterState: isTurningOn()=true
11-22 17:29:00.152  5903  5903 V BluetoothAdapterState: isBleTurningOn()=false
11-22 17:29:00.153  5903  5903 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 17:29:00.153  5903  5915 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 17:29:00.153  5903  5915 D BluetoothAdapterProperties: ScanMode =  20
11-22 17:29:00.153  5903  5915 D BluetoothAdapterProperties: State =  11
11-22 17:29:00.153  5903  5915 D BluetoothAdapterProperties: Setting state to 12
11-22 17:29:00.153  5903  5915 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 17:29:00.154  5903  5915 I BluetoothAdapterState: Entering OnState
,11-22 17:29:00.154  3146  3361 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 17:29:00.154  5903  5919 D BluetoothAdapterProperties: Scan Mode:21
11-22 17:29:00.154  5903  5919 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-22 17:29:00.157  3146  3146 D BluetoothA2dp: Proxy object connected
,11-22 17:29:00.159  5693  5705 D BluetoothPbap: onBluetoothStateChange: up=true
,11-22 17:29:00.165  5903  5903 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 17:29:00.165  3146  3158 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:29:00.165  5903  5903 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 17:29:00.165  5693  5704 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-22 17:29:00.167  5693  5705 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 17:29:00.167  5903  5903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 17:29:00.167  5693  5704 D BluetoothMap: onBluetoothStateChange: up=true
11-22 17:29:00.169   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 17:29:00.169  5903  5903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 17:29:00.169   929   929 D BluetoothA2dp: Proxy object connected
11-22 17:29:00.169  3146  3159 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 17:29:00.170  5903  5903 D ObexServerSockets: Succeed to create listening sockets 
11-22 17:29:00.170  5903  5903 D ObexServerSockets0: startAccept()
11-22 17:29:00.170  5903  5903 D ObexServerSockets0: prepareForNewConnect()
,11-22 17:29:00.171  3797  3812 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:29:00.172   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:29:00.172  5693  5705 D BluetoothPan: onBluetoothStateChange on: true
11-22 17:29:00.173  5903  5903 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 17:29:00.174  5903  5903 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 17:29:00.174  5903  5940 D ObexServerSockets0: Accepting socket connection...
11-22 17:29:00.174  5903  5939 D ObexServerSockets0: Accepting socket connection...
11-22 17:29:00.176  3146  3146 D BluetoothInputDevice: Proxy object connected
11-22 17:29:00.176  3146  3146 D HidProfile: Bluetooth service connected
,11-22 17:29:00.176  5693  5693 D BluetoothInputDevice: Proxy object connected
11-22 17:29:00.176   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:29:00.176  3146  4009 D BluetoothMap: onBluetoothStateChange: up=true
11-22 17:29:00.176  5693  5693 D HidProfile: Bluetooth service connected
11-22 17:29:00.178   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 17:29:00.179  3146  3146 D BluetoothMap: Proxy object connected
11-22 17:29:00.179  5693  5704 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 17:29:00.179  3146  3146 D MapProfile: Bluetooth service connected
11-22 17:29:00.179  3146  3146 D BluetoothMap: getConnectedDevices()
11-22 17:29:00.179  5693  5693 D BluetoothMap: Proxy object connected
11-22 17:29:00.179  5693  5693 D MapProfile: Bluetooth service connected
11-22 17:29:00.179  5693  5693 D BluetoothMap: getConnectedDevices()
11-22 17:29:00.181  3146  4009 D BluetoothPan: onBluetoothStateChange on: true
,11-22 17:29:00.183  5693  5693 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 17:29:00.183  5693  5693 D PanProfile: Bluetooth service connected
11-22 17:29:00.183  5693  5693 D BluetoothA2dp: Proxy object connected
11-22 17:29:00.184  3146  3361 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 17:29:00.184  3146  3146 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 17:29:00.184  3146  3146 D PanProfile: Bluetooth service connected
,11-22 17:29:00.187   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 17:29:00.187  5903  5903 D BluetoothMapService: onReceive
11-22 17:29:00.188  5903  5903 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 17:29:00.188  5903  5903 D BluetoothMapService: STATE_ON
,11-22 17:29:00.190  5903  5943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:29:00.192  5693  5693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 17:29:00.192  5903  5943 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-22 17:29:00.192  5903  5943 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 17:29:00.198  3597  3597 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 17:29:00.200  5693  5693 D DockEventReceiver: finishStartingService: stopping service
,11-22 17:29:00.206  5693  5693 D BluetoothPbap: Proxy object connected
,11-22 17:29:00.206  5693  5693 D PbapServerProfile: Bluetooth service connected
11-22 17:29:00.207  3146  3146 D BluetoothPbap: Proxy object connected
11-22 17:29:00.207  3146  3146 D PbapServerProfile: Bluetooth service connected
,11-22 17:29:00.214  5903  5903 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 17:29:00.214  5903  5903 D ObexServerSockets0: prepareForNewConnect()
11-22 17:29:00.218  5903  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:29:00.230  5903  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 17:29:00.232  5903  5951 I BtOppRfcommListener: Accept thread started.
,11-22 17:29:00.267   929   929 D BluetoothHeadset: Proxy object connected
,11-22 17:29:00.267  5693  5704 D BluetoothHeadset: Proxy object connected
11-22 17:29:00.268  5693  5941 D BluetoothHeadset: Proxy object connected
11-22 17:29:00.268   929   929 D BluetoothHeadset: Proxy object connected
,11-22 17:29:00.268  3146  4009 D BluetoothHeadset: Proxy object connected
,11-22 17:29:00.268  3146  3146 D HeadsetProfile: Bluetooth service connected
11-22 17:29:00.269  3797  3818 D BluetoothHeadset: Proxy object connected
11-22 17:29:00.269   929   929 D BluetoothHeadset: Proxy object connected
11-22 17:29:00.270  5693  5693 D HeadsetProfile: Bluetooth service connected
11-22 17:29:00.271  3797  3996 D BluetoothHeadset: Proxy object connected
11-22 17:29:00.272  5693  5693 D HeadsetProfile: Bluetooth service connected
,11-22 17:29:00.273   929   946 D BluetoothHeadset: Proxy object connected
,11-22 17:29:00.276   929   946 D BluetoothHeadset: Proxy object connected
,11-22 17:29:00.278   929   946 D BluetoothHeadset: Proxy object connected
,11-22 17:29:03.676  4057  4496 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 17:29:04.009  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 17:29:04.015  5635  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 17:29:04.016  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:04.016  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@777de2a removed from the list
11-22 17:29:04.016  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 17:29:04.018  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:29:04.019  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@236941b added. We now have 4 listener(s)
,11-22 17:29:04.019  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:04.023   929  3432 D WifiService: setWifiEnabled: false pid=5635, uid=10077
,11-22 17:29:04.023   929  3432 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 17:29:09.034  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 17:29:09.035   929  3169 D WifiService: setWifiEnabled: true pid=5635, uid=10077
,11-22 17:29:09.035   929  3169 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 17:29:09.045   507   926 D SoftapController: Softap fwReload - Ok
,11-22 17:29:09.050   507   926 D CommandListener: Setting iface cfg
11-22 17:29:09.050   507   926 D CommandListener: Trying to bring down wlan0
,11-22 17:29:09.052   507   926 D CommandListener: Clearing all IP addresses on wlan0
,11-22 17:29:09.058   929  2989 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 17:29:09.746   929  2989 D wifi    : set interface wlan0 flags (UP)
,11-22 17:29:09.751   929  2989 I WifiHAL : Initializing wifi
,11-22 17:29:09.751   929  2989 I WifiHAL : Creating socket
,11-22 17:29:09.753   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 17:29:09.757   929  2989 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 17:29:09.759   929  2989 D wifi    : Did set static halHandle = 0x7f6afc3900
,11-22 17:29:09.759   929  2989 D wifi    : halHandle = 0x7f6afc3900, mVM = 0x7f8760d140, mCls = 0x18ea
,11-22 17:29:09.759   929  2989 D wifi    : array field set
11-22 17:29:09.759   929  2989 I WifiNative-HAL: interface[0] = wlan0
11-22 17:29:09.763   929  5956 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547255761152
,11-22 17:29:09.763   929  5956 D wifi    : waitForHalEvents called, vm = 0x7f8760d140, obj = 0x18ea, env = 0x7f7001d0c0
,11-22 17:29:09.809  5957  5957 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 17:29:09.865   929  2989 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 17:29:09.877  5957  5957 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 17:29:09.927  5957  5957 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 17:29:09.927  5957  5957 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 17:29:09.945   929  2989 D WifiConfigStore: Loading config and enabling all networks 
,11-22 17:29:09.981   929  2989 D WifiConfigStore: loaded 0 passpoint configs
,11-22 17:29:09.982   929  2989 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 17:29:09.982   929  2989 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-22 17:29:09.983   929  2989 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-22 17:29:09.983   929  2989 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-22 17:29:09.983   929  2989 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-22 17:29:09.984   929  2989 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 17:29:09.984   929  2989 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 17:29:09.984   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-22 17:29:09.984   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 17:29:09.984   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 17:29:09.985   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 17:29:09.985   929  2989 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 17:29:09.987   929  2989 D WifiNative-HAL: Setting external_sim to 1
11-22 17:29:09.987   929  2989 D wifi    : setting dfs flag to true, 0x7f6e3ffbc0
,11-22 17:29:09.987   929  2989 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 17:29:09.987  5015  5015 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 17:29:09.987   929  2989 D wifi    : setting scan oui 0x7f6e3ffbc0
11-22 17:29:09.987   929  2989 D WifiHAL : Sending mac address OUI
,11-22 17:29:09.991   929  2989 E native  : do suspend false
,11-22 17:29:10.005   929  2989 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-22 17:29:10.006   929   929 D RttService: SCAN_AVAILABLE : 3
11-22 17:29:10.006   929  3099 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 17:29:10.011   507   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-22 17:29:10.013   507   926 D CommandListener: Setting iface cfg
,11-22 17:29:10.018   929  2988 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-22 17:29:10.018   929  2988 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 17:29:10.026   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=162768 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-22 17:29:10.027   929  2988 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 17:29:10.028   929  2988 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 17:29:10.708   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:11.710   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:12.711   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:13.148  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:29:13.175  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:29:13.188  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:29:13.199  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 17:29:13.238   929  2989 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 17:29:13.239   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-22 17:29:13.239   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 17:29:13.251   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 17:29:13.283   929  2989 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 17:29:13.291  5957  5957 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 17:29:13.711  5957  5957 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 17:29:13.712   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:13.746  5957  5957 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-22 17:29:13.747  5957  5957 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 17:29:13.755   929  2989 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-22 17:29:13.755   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 17:29:13.756   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 17:29:13.771   929  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 17:29:13.782   507   926 D CommandListener: Setting iface cfg
,11-22 17:29:13.787   929  2989 D WifiStateMachine: Start Dhcp Watchdog 3
,11-22 17:29:13.797   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-22 17:29:13.797   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-22 17:29:13.797   929  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
11-22 17:29:13.798   929  5962 D DhcpClient: Receive thread started
,11-22 17:29:13.878   929  2989 E native  : do suspend false
,11-22 17:29:13.889   929  5961 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 17:29:13.903   929  5962 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-22 17:29:13.904   929  5961 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-22 17:29:13.906   929  5961 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 17:29:13.917   929  5962 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 17:29:13.918   929  5961 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 17:29:13.922   507   926 D CommandListener: Setting iface cfg
,11-22 17:29:13.926   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 17:29:13.929   929  5961 D DhcpClient: Scheduling renewal in 86399s
,11-22 17:29:13.943   929  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-22 17:29:13.944   929  2989 D WifiConfigStore: No blacklist allowed without epno enabled
,11-22 17:29:13.944   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 17:29:13.946   929  2991 D ConnectivityService: Adding iface wlan0 to network 102
11-22 17:29:13.950   929  2989 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 17:29:13.988   929  2991 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 17:29:13.989   929  2991 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-22 17:29:13.992   929  2991 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-22 17:29:13.994   929  2991 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-22 17:29:13.996   929  2991 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-22 17:29:14.007   929  2991 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:29:14.012   929  2991 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-22 17:29:14.012   929  2991 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-22 17:29:14.013   929  2991 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-22 17:29:14.013   929  2989 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 17:29:14.013   929  2991 D ConnectivityService:    accepting network in place of null
11-22 17:29:14.013   929  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 17:29:14.013   929  2991 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 17:29:14.019   929  5960 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166761, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 17:29:14.044   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 17:29:14.052  5635  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 17:29:14.054  5635  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 17:29:14.054  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:29:14.055  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@236941b removed from the list
11-22 17:29:14.055  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:29:14.059  5635  5682 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-22 17:29:14.060  5635  5682 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-22 17:29:14.063  5635  5682 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2e7491b Bundle[{}]
11-22 17:29:14.063  5635  5682 I io.jxcore.node.LifeCycleMonitor: start: OK
11-22 17:29:14.064  5635  5682 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-22 17:29:14.064  5635  5682 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-22 17:29:14.066  5635  5682 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-22 17:29:14.066  5635  5682 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-22 17:29:14.068  5635  5682 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-22 17:29:14.073   507   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 17:29:14.076  5635  5682 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-22 17:29:14.076   929  2991 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-22 17:29:14.077  3769  3908 W QCNEJ   : |CORE| network available: 102
11-22 17:29:14.077   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 17:29:14.077  5635  5682 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-22 17:29:14.077  5635  5682 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-22 17:29:14.078   929  2991 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-22 17:29:14.079  3769  3908 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 17:29:14.081   929   946 D Tethering: MasterInitialState.processMessage what=3
11-22 17:29:14.082  3769  3908 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 17:29:14.082  3769  3908 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-22 17:29:14.084  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.084  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3f79b8 added. We now have 3 listener(s)
,11-22 17:29:14.095   929  5959 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-22 17:29:14.087  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 17:29:14.096  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 17:29:14.096  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 17:29:14.096  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:29:14.096  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d1391 added. We now have 4 listener(s)
11-22 17:29:14.096  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.096  5063  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 17:29:14.097  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 17:29:14.097  3991  3991 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-22 17:29:14.096  5063  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 17:29:14.098  5063  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 17:29:14.099  5063  5085 E SarControlService: no key has been found,reset the power
11-22 17:29:14.099  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.099  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8db2f6 added. We now have 4 listener(s)
11-22 17:29:14.099  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 17:29:14.099  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-22 17:29:14.099  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 17:29:14.099  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 17:29:14.099  5088  5088 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 17:29:14.100  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.100  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.100  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.100  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:29:14.100  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22056f7 added. We now have 5 listener(s)
11-22 17:29:14.100  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.100  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:29:14.100  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:14.100  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:29:14.100  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.100  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 17:29:14.100  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.100  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3f79b8 removed from the list
11-22 17:29:14.100  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.100  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d1391 removed from the list
11-22 17:29:14.100  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:29:14.100  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.101  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.101  5063  5100 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 17:29:14.101  5063  5100 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 17:29:14.101  5063  5100 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 17:29:14.101  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 17:29:14.101  5088  5088 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 17:29:14.101  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.101  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.102  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.102  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.102  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 17:29:14.092  3874  3874 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 17:29:14.102  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.102  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d1391 not in the list
11-22 17:29:14.102  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.102  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.103  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.103  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.103  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.103  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.103  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.103  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.103  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22056f7 removed from the list
11-22 17:29:14.103  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.104  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.104  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.104  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8db2f6 removed from the list
,11-22 17:29:14.104  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.104  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4e7964 added. We now have 3 listener(s)
11-22 17:29:14.105  3874  3874 D SystemUpdateService: onCreate
11-22 17:29:14.105  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.105  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.105  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.105  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000f003000000000000ffffffff]
11-22 17:29:14.106  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:29:14.106  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-22 17:29:14.106  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbe57cd added. We now have 4 listener(s)
11-22 17:29:14.106  5088  5102 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-22 17:29:14.106  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.106  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 17:29:14.106  5063  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 17:29:14.106  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 17:29:14.107  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.107  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5a0882 added. We now have 4 listener(s)
11-22 17:29:14.108  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.108  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 17:29:14.108  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.108  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:29:14.108  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1796b93 added. We now have 5 listener(s)
11-22 17:29:14.108  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.108  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:29:14.108  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 17:29:14.108  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 17:29:14.108  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:29:14.109  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 17:29:14.109  5088  5102 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e35a307 HexData = [00000000f103000000000000ffffffff]
,11-22 17:29:14.109  5088  5102 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 17:29:14.109  5088  5102 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-22 17:29:14.109  5088  5088 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 17:29:14.109  5063  5073 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 17:29:14.109  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 17:29:14.110  3874  3874 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-22 17:29:14.111  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 17:29:14.112  5635  5682 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 17:29:14.112  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 17:29:14.116  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.116  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 17:29:14.116  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 17:29:14.116  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 17:29:14.116  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 17:29:14.119  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.119  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 17:29:14.119  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-22 17:29:14.119  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 17:29:14.119  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 17:29:14.119  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.119  5635  5682 D BluetoothAdapter: STATE_ON
,11-22 17:29:14.120  3874  5972 I SystemUpdateService: active receiver: enabled
,11-22 17:29:14.123  5903  5942 D BtGatt.GattService: registerClient() - UUID=d70fb57a-c95f-4c20-baa8-c8e8129d5627
,11-22 17:29:14.123  5903  5919 D BtGatt.GattService: onClientRegistered() - UUID=d70fb57a-c95f-4c20-baa8-c8e8129d5627, clientIf=5
,11-22 17:29:14.124  5635  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 17:29:14.125  5903  5914 D BtGatt.GattService: start scan with filters
11-22 17:29:14.126  3874  5972 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 17:29:14.129  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 17:29:14.129  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.129  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 17:29:14.129  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.129  5903  5922 D BtGatt.ScanManager: handling starting scan
11-22 17:29:14.129  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 17:29:14.129  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 17:29:14.129  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.129  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 17:29:14.129  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 17:29:14.129  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 17:29:14.129  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.129  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.129  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.130  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 17:29:14.130  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.130  5903  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a775dcc
,11-22 17:29:14.132  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.132  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:29:14.132  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.132  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.132  5635  5682 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 17:29:14.132  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:14.132  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 17:29:14.132  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:29:14.133  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 17:29:14.133  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.133  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.133  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 17:29:14.134  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.134  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.134  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.134  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 17:29:14.134  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:29:14.134  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.134  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 17:29:14.134  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 17:29:14.134  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.134  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.134  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.134  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 17:29:14.135  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.135  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:29:14.135  5903  5938 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 17:29:14.135  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 17:29:14.136  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:29:14.136  5903  5914 D BtGatt.GattService: stopScan() - queue size =1
11-22 17:29:14.136  3874  3874 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-22 17:29:14.137  5903  5938 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 17:29:14.137  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 17:29:14.137  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.137  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 17:29:14.137  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.137  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.138  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.138  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.138  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 17:29:14.138  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.138  5903  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 17:29:14.138  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.138  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.138  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.138  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 17:29:14.138  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 17:29:14.138  5903  5922 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 17:29:14.141  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 17:29:14.141  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.142  3874  5972 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-22 17:29:14.142  3874  5972 I SystemUpdateService: now status is 0 (complete)
11-22 17:29:14.142  3874  5972 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 17:29:14.142  3874  5972 I SystemUpdateService: file has been verified
11-22 17:29:14.142  3874  5972 I SystemUpdateService: OTA package size = 21989297
11-22 17:29:14.143  5903  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 17:29:14.143  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.144  5903  5922 D BtGatt.ScanManager: Starting BLE batch scan
11-22 17:29:14.144  5903  5922 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 17:29:14.144  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.144  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 17:29:14.145  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.145  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.145  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:29:14.145  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:29:14.145  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 17:29:14.145  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.145  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 17:29:14.145  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 17:29:14.145  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.145  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.145  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.145  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:29:14.145  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.145  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.146  3874  5414 I iu.UploadsManager: num queued entries: 0
,11-22 17:29:14.146  3874  5414 I iu.UploadsManager: num updated entries: 0
11-22 17:29:14.147  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:29:14.147  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:14.147  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:29:14.147  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.147  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 17:29:14.147  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.147  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4e7964 removed from the list
11-22 17:29:14.147  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.147  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbe57cd removed from the list
11-22 17:29:14.147  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:29:14.147  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.147  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.147   929  5959 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 16:29:14 GMT], X-Android-Received-Millis=[1479832154147], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479832154120]}
,11-22 17:29:14.148  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.148  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.148   929  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 17:29:14.148  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.148   929  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-22 17:29:14.148  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.148  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.148   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-22 17:29:14.148  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.148  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.148  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.148  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.148  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbe57cd not in the list
11-22 17:29:14.148  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.148  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.149   929  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-22 17:29:14.150  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.150  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.150  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.150  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.150  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.150  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.150  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1796b93 removed from the list
11-22 17:29:14.150  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.150  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.150  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.150  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5a0882 removed from the list
11-22 17:29:14.151  3874  3874 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-22 17:29:14.151  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.151  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64d90fc added. We now have 3 listener(s)
,11-22 17:29:14.152  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.152  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.152  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.152  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 17:29:14.152  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb385 added. We now have 4 listener(s)
11-22 17:29:14.152  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.154  5903  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 17:29:14.154  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 17:29:14.154  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.155  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 17:29:14.155  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5c25da added. We now have 4 listener(s)
11-22 17:29:14.155  3874  3874 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-22 17:29:14.156  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.156  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.156  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.156  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:29:14.156  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d60ba0b added. We now have 5 listener(s)
,11-22 17:29:14.156  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.156  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:29:14.157  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:29:14.157  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 17:29:14.157  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 17:29:14.157  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:29:14.157  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 17:29:14.159  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 17:29:14.160  5759  5759 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-22 17:29:14.161  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 17:29:14.161  5635  5682 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 17:29:14.161  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 17:29:14.161  5903  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 17:29:14.161  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.162  5903  5922 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 17:29:14.165  5759  5759 D SprintDMHelper: simOperator: 
,11-22 17:29:14.165  5759  5759 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 17:29:14.165  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.165  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 17:29:14.165  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 17:29:14.166  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 17:29:14.166  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 17:29:14.167  5903  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 17:29:14.167  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.168  5903  5919 E BtGatt.ContextMap: Context not found for ID 5
11-22 17:29:14.168  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.169  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 17:29:14.169  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 17:29:14.169  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 17:29:14.169  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 17:29:14.169  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.169  5635  5682 D BluetoothAdapter: STATE_ON
,11-22 17:29:14.171  5903  5913 D BtGatt.GattService: registerClient() - UUID=8a5500d3-b9b6-4e73-9fdf-c58487b1dd80
11-22 17:29:14.171  5903  5919 D BtGatt.GattService: onClientRegistered() - UUID=8a5500d3-b9b6-4e73-9fdf-c58487b1dd80, clientIf=5
11-22 17:29:14.172  5635  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 17:29:14.174  5903  5942 D BtGatt.GattService: start scan with filters
11-22 17:29:14.175  3874  5414 I iu.SyncManager: NEXT; no task
11-22 17:29:14.176  5903  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 17:29:14.176  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.176  5903  5922 D BtGatt.ScanManager: stopping BLe Batch
,11-22 17:29:14.178  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 17:29:14.178  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.178  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 17:29:14.178  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.178  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 17:29:14.178  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 17:29:14.178  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.178  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 17:29:14.178  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 17:29:14.179  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 17:29:14.179  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.179  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.179  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.179  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-22 17:29:14.179  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.180  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.180  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:29:14.180  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.181  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.181  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:29:14.181  5635  5682 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 17:29:14.181  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:29:14.181  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.181  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:14.181  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:29:14.181  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.181  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 17:29:14.181  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:29:14.181  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.181  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.181  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64d90fc removed from the list
11-22 17:29:14.181  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.181  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb385 removed from the list
11-22 17:29:14.181  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:29:14.181  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-22 17:29:14.181  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:29:14.181  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.182  5903  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 17:29:14.182  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,11-22 17:29:14.182  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.182  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 17:29:14.182  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:29:14.182  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:29:14.182  5903  5922 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 17:29:14.182  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.183  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.183  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.183  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.183  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb385 not in the list
11-22 17:29:14.183  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.183  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 17:29:14.183  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.184  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:29:14.184  5903  5913 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 17:29:14.184  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 17:29:14.185  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:29:14.185  5903  5914 D BtGatt.GattService: stopScan() - queue size =0
11-22 17:29:14.187  5903  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 17:29:14.187  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.188  5903  5922 D BtGatt.ScanManager: handling starting scan
11-22 17:29:14.188  5903  5913 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 17:29:14.188  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 17:29:14.188  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.188  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 17:29:14.188  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.,le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.189  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 17:29:14.189  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 17:29:14.189  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 17:29:14.190  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.191  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.191  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:29:14.191  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.191  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.191  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.191  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.191  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:29:14.191  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:29:14.191  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d60ba0b removed from the list
11-22 17:29:14.191  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.191  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:29:14.192  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.192  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.192  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 17:29:14.192  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5c25da removed from the list
11-22 17:29:14.192  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.192  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-22 17:29:14.192  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 17:29:14.192  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.192  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.192  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.192  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:29:14.192  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.192  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf50394 added. We now have 3 listener(s)
11-22 17:29:14.192  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.192  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.193  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 17:29:14.193  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.193  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.193  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.193  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.193  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.193  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:29:14.193  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e1ce3d added. We now have 4 listener(s)
11-22 17:29:14.193  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.194  5903  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 17:29:14.194  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.194  3874  5972 I SystemUpdateService: showing system update notification
11-22 17:29:14.194  5903  5922 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 17:29:14.197  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 17:29:14.198  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.198  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b299632 added. We now have 4 listener(s)
11-22 17:29:14.199  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.199  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.199  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.199  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:29:14.199  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9245f83 added. We now have 5 listener(s)
11-22 17:29:14.199  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.199  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 17:29:14.199  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 17:29:14.199  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 17:29:14.200  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 17:29:14.200  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 17:29:14.200  5903  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 17:29:14.200  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.201  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 17:29:14.201  5903  5922 D BtGatt.ScanManager: Starting BLE batch scan
11-22 17:29:14.201  5903  5922 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 17:29:14.202  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 17:29:14.202  5635  5682 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 17:29:14.203  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-22 17:29:14.205  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.205  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 17:29:14.205  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 17:29:14.205  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 17:29:14.205  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 17:29:14.208   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-22 17:29:14.209  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.209  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 17:29:14.209  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-22 17:29:14.209  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 17:29:14.209  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 17:29:14.209  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.210  3874  3874 D SystemUpdateService: onDestroy
,11-22 17:29:14.210  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:29:14.210  5903  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 17:29:14.210  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.212  5903  5913 D BtGatt.GattService: registerClient() - UUID=e32ca350-8f94-4bfe-bd69-4ec2196a8db8
,11-22 17:29:14.214  5903  5919 D BtGatt.GattService: onClientRegistered() - UUID=e32ca350-8f94-4bfe-bd69-4ec2196a8db8, clientIf=5
11-22 17:29:14.214  5635  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 17:29:14.214  5903  5914 D BtGatt.GattService: start scan with filters
11-22 17:29:14.215  5903  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 17:29:14.215  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.215  3597  5984 I VacuumService: Vacuum at: now=1479832154215 tag=VacuumService
11-22 17:29:14.216  5903  5922 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 17:29:14.217  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 17:29:14.217  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.217  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 17:29:14.217  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.217  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 17:29:14.217  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 17:29:14.217  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.217  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 17:29:14.217  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 17:29:14.217  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 17:29:14.217  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.218  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.218  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.218  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 17:29:14.218  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.220  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.220  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 17:29:14.220  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.220  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.221  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.221  5903  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 17:29:14.221  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.222  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 17:29:14.222  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:14.222  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:29:14.223  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.223  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:29:14.223  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:29:14.223  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 17:29:14.223  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.223  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf50394 removed from the list
11-22 17:29:14.223  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.223  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e1ce3d removed from the list
11-22 17:29:14.223  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:29:14.223  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:29:14.223  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:29:14.223  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.223  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 17:29:14.223  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 17:29:14.223  5635  5682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 17:29:14.223  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 17:29:14.223  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.224  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.225  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.225  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.225  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.225  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 17:29:14.225  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.225  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.225  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e1ce3d not in the list
11-22 17:29:14.225  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 17:29:14.225  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.225  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 17:29:14.225  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.227  5635  5682 D BluetoothAdapter: STATE_ON
11-22 17:29:14.227  5903  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 17:29:14.227  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.227  5903  5913 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 17:29:14.227  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 17:29:14.227  5903  5922 D BtGatt.ScanManager: stopping BLe Batch
11-22 17:29:14.228  5635  5682 D BluetoothAdapter: STATE_ON
,11-22 17:29:14.229  5903  5914 D BtGatt.GattService: stopScan() - queue size =0
,11-22 17:29:14.230  5903  5938 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 17:29:14.230  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 17:29:14.230  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.230  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 17:29:14.230  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.230  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.231  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-22 17:29:14.231  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.231  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 17:29:14.231  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.231  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.231  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.231  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 17:29:14.231  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 17:29:14.232  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 17:29:14.232  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.233  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.233  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:29:14.233  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.233  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.233  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.233  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.233  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.233  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9245f83 removed from the list
11-22 17:29:14.233  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:29:14.233  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.233  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.233  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 17:29:14.234  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.234  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b299632 removed from the list
11-22 17:29:14.234  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 17:29:14.234  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.234  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 17:29:14.234  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscov,erer: updateState: stateSet: [SCANNING]
11-22 17:29:14.234  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.234  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.234  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.234  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.234  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@895312c added. We now have 3 listener(s)
11-22 17:29:14.234  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 17:29:14.234  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.234  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.234  5903  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 17:29:14.235  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.235  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.235  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.235  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.235  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:29:14.235  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8987f5 added. We now have 4 listener(s)
11-22 17:29:14.235  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.235  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 17:29:14.235  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.235  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 17:29:14.235  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 17:29:14.236  5903  5922 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 17:29:14.236  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 17:29:14.236  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e79b98a added. We now have 4 listener(s)
,11-22 17:29:14.237  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 17:29:14.237  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 17:29:14.237  5635  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 17:29:14.237  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 17:29:14.237  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b183bfb added. We now have 5 listener(s)
11-22 17:29:14.237  5635  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 17:29:14.237  5635  5682 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 17:29:14.237  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:14.237  5635  5682 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 17:29:14.237  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.237  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.237  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.237  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@895312c removed from the list
11-22 17:29:14.237  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.237  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8987f5 removed from the list
11-22 17:29:14.237  5635  5682 D io.jxcore.node.ConnectivityMonitor: stop
11-22 17:29:14.237  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.237  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.238  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.238  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.238  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.238  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.238  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.238  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 17:29:14.238  5635  5682 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8987f5 not in the list
11-22 17:29:14.238  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.238  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.240  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.240  5903  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 17:29:14.240  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.240  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.240  5635  5682 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-22 17:29:14.240  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 17:29:14.240  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 17:29:14.240  5635  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 17:29:14.240  5635  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b183bfb removed from the list
11-22 17:29:14.240  5635  5682 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 17:29:14.240  5635  5682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 17:29:14.240  5635  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 17:29:14.240  5635  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e79b98a removed from the list
11-22 17:29:14.241  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 17:29:14.241  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 17:29:14.241  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-22 17:29:14.241  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:29:14.241  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-22 17:29:14.241  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:14.243  5903  5922 D BtGatt.ScanManager: handling starting scan
,11-22 17:29:14.247  5903  5919 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-22 17:29:14.247  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.248  5903  5922 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-22 17:29:14.252  5903  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 17:29:14.252  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.252  5903  5922 D BtGatt.ScanManager: Starting BLE batch scan
11-22 17:29:14.252  5903  5922 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 17:29:14.259  5903  5919 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-22 17:29:14.259  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.263  5903  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 17:29:14.263  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.264  5903  5922 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 17:29:14.270  5903  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 17:29:14.270  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.270  5903  5919 E BtGatt.ContextMap: Context not found for ID 5
,11-22 17:29:14.275  5903  5919 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 17:29:14.275  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.276  5903  5922 D BtGatt.ScanManager: stopping BLe Batch
,11-22 17:29:14.278  3597  5987 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-22 17:29:14.280  5903  5919 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 17:29:14.280  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 17:29:14.280  5903  5922 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 17:29:14.284  5903  5919 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 17:29:14.284  5903  5919 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 17:29:14.305  3597  5985 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-22 17:29:14.308  3597  5985 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-22 17:29:14.328  3597  5985 W Uploader:  no longer exists, so no auth token.
,11-22 17:29:14.334  3597  5987 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 17:29:14.375  5015  5979 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 17:29:14.594  3597  5989 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 17:29:14.646  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 17:29:14.693  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 17:29:14.713   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:14.734  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 17:29:14.748  3597  5985 W Uploader:  no longer exists, so no auth token.
,11-22 17:29:14.757  3597  5987 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 17:29:14.833  3597  5989 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 17:29:14.901  3597  5987 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 17:29:14.980  3597  5989 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 17:29:15.713   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 17:29:16.334  5635  5996 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 17:29:16.334  5635  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:16.819   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:29:17.195  5635  5996 W !!      : call onHalfStreamCopied
,11-22 17:29:17.195  5635  5996 I testCopyDataAndClose: closing input stream
,11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 17:29:17.974  5635  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 17:29:22.017   929  2991 D ConnectivityService: handlePromptUnvalidated 102
,11-22 17:29:22.315  5635  5997 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:22.315  5635  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:24.315  5635  5682 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-22 17:29:24.315  5635  5682 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:24.315  5635  5682 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-22 17:29:24.384  5635  5997 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-22 17:29:24.385  5635  5997 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:24.385  5635  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-22 17:29:24.504  5635  5998 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 17:29:24.504  5635  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:25.029   929  2989 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 17:29:26.125  5635  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 17:29:30.749  5635  5999 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:30.749  5635  5999 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 17:29:30.750  5635  5999 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-22 17:29:30.751  5635  5999 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 17:29:30.751  5635  5999 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:30.751  5635  5999 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-22 17:29:30.752  5635  5682 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-22 17:29:30.755  5635  6000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:30.755  5635  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 17:29:30.756  5635  6000 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-22 17:29:30.756  5635  6000 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:30.756  5635  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 17:29:30.756  5635  6000 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-22 17:29:30.757  5635  6000 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 17:29:30.757  5635  6000 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 17:29:30.762  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-22 17:29:30.762  5635  5682 I jxcore-log: 
,11-22 17:29:30.762  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-22 17:29:30.762  5635  5682 I jxcore-log: 
11-22 17:29:30.762  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-22 17:29:30.762  5635  5682 I jxcore-log: 
11-22 17:29:30.763  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-22 17:29:30.763  5635  5682 I jxcore-log: 
,11-22 17:29:30.763  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG UnitTest_app: 'Total duration:  92242'
11-22 17:29:30.763  5635  5682 I jxcore-log: 
11-22 17:29:30.765  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-22 17:29:30.765  5635  5682 I jxcore-log: 
11-22 17:29:30.769  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 17:29:30.769  5635  5682 I jxcore-log: 
,11-22 17:29:30.770  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 17:29:30.770  5635  5682 I jxcore-log: 
11-22 17:29:30.770  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 17:29:30.770  5635  5682 I jxcore-log: 
11-22 17:29:30.770  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 17:29:30.770  5635  5682 I jxcore-log: 
11-22 17:29:30.771  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.771  5635  5682 I jxcore-log: 
11-22 17:29:30.771  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 17:29:30.771  5635  5682 I jxcore-log: 
11-22 17:29:30.771  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.771  5635  5682 I jxcore-log: 
11-22 17:29:30.771  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 17:29:30.771  5635  5682 I jxcore-log: 
11-22 17:29:30.772  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 17:29:30.772  5635  5682 I jxcore-log: 
11-22 17:29:30.772  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 17:29:30.772  5635  5682 I jxcore-log: 
11-22 17:29:30.772  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-22 17:29:30.772  5635  5682 I jxcore-log: 
11-22 17:29:30.773  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.773  5635  5682 I jxcore-log: 
11-22 17:29:30.773  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 17:29:30.773  5635  5682 I jxcore-log: 
11-22 17:29:30.773  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.773  5635  5682 I jxcore-log: 
,11-22 17:29:30.773  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 17:29:30.773  5635  5682 I jxcore-log: 
11-22 17:29:30.773  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.773  5635  5682 I jxcore-log: 
11-22 17:29:30.774  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 17:29:30.774  5635  5682 I jxcore-log: 
11-22 17:29:30.774  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 17:29:30.774  5635  5682 I jxcore-log: 
11-22 17:29:30.774  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 17:29:30.774  5635  5682 I jxcore-log: 
11-22 17:29:30.774  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 17:29:30.774  5635  5682 I jxcore-log: 
11-22 17:29:30.775  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 17:29:30.775  5635  5682 I jxcore-log: 
11-22 17:29:30.775  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 17:29:30.775  5635  5682 I jxcore-log: 
,11-22 17:29:30.775  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 17:29:30.775  5635  5682 I jxcore-log: 
11-22 17:29:30.776  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 17:29:30.776  5635  5682 I jxcore-log: 
,11-22 17:29:30.777  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 17:29:30.777  5635  5682 I jxcore-log: 
,11-22 17:29:30.777  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 17:29:30.777  5635  5682 I jxcore-log: 
11-22 17:29:30.778  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 17:29:30.778  5635  5682 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,11-22 17:29:30.778  5635  5682 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 17:29:30.778  5635  5682 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-22 17:29:30.778  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 17:29:30.778  5635  5682 I jxcore-log: 
11-22 17:29:30.778  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.778  5635  5682 I jxcore-log: 
11-22 17:29:30.779  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 17:29:30.779  5635  5682 I jxcore-log: 
,11-22 17:29:30.779  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.779  5635  5682 I jxcore-log: 
11-22 17:29:30.779  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 17:29:30.779  5635  5682 I jxcore-log: 
11-22 17:29:30.779  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-22 17:29:30.779  5635  5682 I jxcore-log: 
,11-22 17:29:30.784  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-22 17:29:30.784  5635  5682 I jxcore-log: 
11-22 17:29:30.785  5635  5682 I jxcore-log: 2016-11-22 16:29:30 - WARN testUtils: 'myNameCallback not set!'
11-22 17:29:30.785  5635  5682 I jxcore-log: 
,11-22 17:29:30.788  5635  5635 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-22 17:29:32.864  5635  5682 I jxcore-log: 2016-11-22 16:29:32 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-22 17:29:32.864  5635  5682 I jxcore-log: 
,11-22 17:29:32.865  5635  5682 I jxcore-log: 2016-11-22 16:29:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-22 17:29:32.865  5635  5682 I jxcore-log: 
,11-22 17:29:33.211  5635  5682 I jxcore-log: 2016-11-22 16:29:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-22 17:29:33.211  5635  5682 I jxcore-log: 
,11-22 17:29:33.223  5635  5682 I jxcore-log: 2016-11-22 16:29:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-22 17:29:33.223  5635  5682 I jxcore-log: 
,11-22 17:29:34.336  5635  5682 I jxcore-log: 2016-11-22 16:29:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-22 17:29:34.336  5635  5682 I jxcore-log: 
,11-22 17:29:34.530  5635  5682 I jxcore-log: 2016-11-22 16:29:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-22 17:29:34.530  5635  5682 I jxcore-log: 
,11-22 17:29:34.535  5635  5682 I jxcore-log: 2016-11-22 16:29:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-22 17:29:34.535  5635  5682 I jxcore-log: 
,11-22 17:29:34.540  5635  5682 I jxcore-log: 2016-11-22 16:29:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-22 17:29:34.540  5635  5682 I jxcore-log: 
,11-22 17:29:35.027  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-22 17:29:35.027  5635  5682 I jxcore-log: 
,11-22 17:29:35.072  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-22 17:29:35.072  5635  5682 I jxcore-log: 
,11-22 17:29:35.085  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-22 17:29:35.085  5635  5682 I jxcore-log: 
,11-22 17:29:35.089  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-22 17:29:35.089  5635  5682 I jxcore-log: 
,11-22 17:29:35.360  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-22 17:29:35.360  5635  5682 I jxcore-log: 
,11-22 17:29:35.489  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-22 17:29:35.489  5635  5682 I jxcore-log: 
,11-22 17:29:35.715   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:35.869  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-22 17:29:35.869  5635  5682 I jxcore-log: 
,11-22 17:29:35.878  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-22 17:29:35.878  5635  5682 I jxcore-log: 
,11-22 17:29:35.881  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-22 17:29:35.881  5635  5682 I jxcore-log: 
,11-22 17:29:35.887  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-22 17:29:35.887  5635  5682 I jxcore-log: 
,11-22 17:29:35.893  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-22 17:29:35.893  5635  5682 I jxcore-log: 
,11-22 17:29:35.921  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-22 17:29:35.921  5635  5682 I jxcore-log: 
,11-22 17:29:35.956  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-22 17:29:35.956  5635  5682 I jxcore-log: 
,11-22 17:29:35.963  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-22 17:29:35.963  5635  5682 I jxcore-log: 
,11-22 17:29:35.970  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-22 17:29:35.970  5635  5682 I jxcore-log: 
,11-22 17:29:35.985  5635  5682 I jxcore-log: 2016-11-22 16:29:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-22 17:29:35.985  5635  5682 I jxcore-log: 
,11-22 17:29:36.001  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-22 17:29:36.001  5635  5682 I jxcore-log: 
,11-22 17:29:36.007  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-22 17:29:36.007  5635  5682 I jxcore-log: 
,11-22 17:29:36.012  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-22 17:29:36.012  5635  5682 I jxcore-log: 
,11-22 17:29:36.025  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-22 17:29:36.025  5635  5682 I jxcore-log: 
,11-22 17:29:36.043  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-22 17:29:36.043  5635  5682 I jxcore-log: 
,11-22 17:29:36.057  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-22 17:29:36.057  5635  5682 I jxcore-log: 
,11-22 17:29:36.068  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-22 17:29:36.068  5635  5682 I jxcore-log: 
,11-22 17:29:36.080  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-22 17:29:36.080  5635  5682 I jxcore-log: 
,11-22 17:29:36.090  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-22 17:29:36.090  5635  5682 I jxcore-log: 
,11-22 17:29:36.104  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-22 17:29:36.104  5635  5682 I jxcore-log: 
,11-22 17:29:36.113  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-22 17:29:36.113  5635  5682 I jxcore-log: 
,11-22 17:29:36.120  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-22 17:29:36.120  5635  5682 I jxcore-log: 
,11-22 17:29:36.142  5635  5682 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-22 17:29:36.143  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO testUtils: 'BLE multiple advertisement supported'
11-22 17:29:36.143  5635  5682 I jxcore-log: 
,11-22 17:29:36.177  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-22 17:29:36.177  5635  5682 I jxcore-log: 
,11-22 17:29:36.503  5635  5682 I jxcore-log: 2016-11-22 16:29:36 - DEBUG CoordinatedClient: 'connected to the test server'
11-22 17:29:36.503  5635  5682 I jxcore-log: 
,11-22 17:29:36.716   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:37.717   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:38.718   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:39.719   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:29:40.720   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 17:29:53.990   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:30:01.039   929   942 I ActivityManager: Start proc 6009:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,11-22 17:30:01.102  6009  6009 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,11-22 17:30:01.131  6009  6009 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
11-22 17:30:01.131  6009  6009 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-22 17:30:01.131  6009  6009 I GAv4    :   adb logcat -s GAv4
,11-22 17:30:01.147  6009  6009 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-22 17:30:01.152  6009  6009 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-22 17:30:01.166  6009  6024 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-22 17:30:01.238   929  3156 I ActivityManager: Killing 5508:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-22 17:30:05.720   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 17:30:05.721   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 17:30:15.722   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:16.723   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:17.724   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:18.725   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:19.726   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:20.727   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 17:30:23.386   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:30:25.729   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:26.417   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:30:26.730   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:27.732   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:28.733   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:29.735   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:30.736   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 17:30:33.998   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:30:40.737   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:41.739   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:42.740   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:43.742   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:44.743   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:30:45.744   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 17:30:53.999   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:30:59.729   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:31:00.746   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:01.747   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:02.748   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:02.764   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:31:03.750   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:04.751   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:05.752   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 17:31:14.850   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:31:17.889   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:31:25.753   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:26.755   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:27.757   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:28.758   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:29.760   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:31:30.761   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 17:31:34.004   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:31:39.081   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:31:42.115   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:31:54.007   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:31:55.762   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 17:31:55.762   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 17:32:10.763   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:11.764   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:12.766   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:13.767   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:14.010   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:32:14.768   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:15.769   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 17:32:20.770   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:21.772   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:22.773   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:23.775   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:24.776   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:25.777   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 17:32:35.779   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:36.780   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:37.781   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:38.783   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:39.785   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:40.786   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 17:32:54.014   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:32:54.755   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:32:55.788   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:56.789   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:57.790   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:57.800   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:32:58.791   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:32:59.792   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:33:00.793   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 17:33:14.017   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:33:20.795   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:33:21.796   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:33:22.798   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:33:23.799   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:33:24.801   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:33:25.802   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 17:33:34.020   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:33:34.118   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:33:37.138   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:33:50.803   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-22 17:33:50.803   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 17:33:54.023   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:34:04.392   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:34:07.430   929  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 17:34:10.804   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:34:11.806   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:34:12.807   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:34:13.809   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:34:14.024   929  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 17:34:14.358  5635  5682 I jxcore-log: 2016-11-22 16:34:14 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-22 17:34:14.358  5635  5682 I jxcore-log: 
,11-22 17:34:14.563  5635  5682 I jxcore-log: 2016-11-22 16:34:14 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 17:34:14.563  5635  5682 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 17:34:14.563  5635  5682 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 17:34:14.563  5635  5682 I jxcore-log: emit@events.js:82:1
11-22 17:34:14.563  5635  5682 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 17:34:14.563  5635  5682 I jxcore-log: emit@events.js:82:1''
11-22 17:34:14.563  5635  5682 I jxcore-log: 
,11-22 17:34:14.565  5635  5682 I jxcore-log: 2016-11-22 16:34:14 - DEBUG CoordinatedClient: 'test client failed'
11-22 17:34:14.565  5635  5682 I jxcore-log: 
,11-22 17:34:14.575  5635  5682 I jxcore-log: 2016-11-22 16:34:14 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 17:34:14.575  5635  5682 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 17:34:14.575  5635  5682 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 17:34:14.575  5635  5682 I jxcore-log: emit@events.js:82:1
11-22 17:34:14.575  5635  5682 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 17:34:14.575  5635  5682 I jxcore-log: emit@events.js:82:1''
11-22 17:34:14.575  5635  5682 I jxcore-log: 
,11-22 17:34:14.576  5635  5682 I jxcore-log: 2016-11-22 16:34:14 - DEBUG CoordinatedClient: 'test client failed'
11-22 17:34:14.576  5635  5682 I jxcore-log: 
,11-22 17:34:14.581  5635  5682 I jxcore-log: 2016-11-22 16:34:14 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 17:34:14.581  5635  5682 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 17:34:14.581  5635  5682 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 17:34:14.581  5635  5682 I jxcore-log: emit@events.js:82:1
11-22 17:34:14.581  5635  5682 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 17:34:14.581  5635  5682 I jxcore-log: emit@events.js:82:1''
11-22 17:34:14.581  5635  5682 I jxcore-log: 
,11-22 17:34:14.582  5635  5682 I jxcore-log: 2016-11-22 16:34:14 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-22 17:34:14.582  5635  5682 I jxcore-log: 
,11-22 17:34:14.809   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 17:34:15.138  6028  6028 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-22 17:34:15.143  6028  6028 D AndroidRuntime: CheckJNI is OFF
,11-22 17:34:15.171  6028  6028 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-22 17:34:15.205  6028  6028 I Radio-JNI: register_android_hardware_Radio DONE
,11-22 17:34:15.220  6028  6028 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-22 17:34:15.228   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-22 17:34:15.229   929   942 I ActivityManager: Killing 5635:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-22 17:34:15.332   929  3432 I WindowState: WIN DEATH: Window{dd07f17 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-22 17:34:15.332   929  3169 D GraphicsStats: Buffer count: 2
11-22 17:34:15.332   929  2990 D WifiService: Client connection lost with reason: 4
,11-22 17:34:15.346   929   942 W ActivityManager: Force removing ActivityRecord{1ca2a0c u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-22 17:34:15.377   929   952 I art     : Starting a blocking GC Explicit
,11-22 17:34:15.384   929   940 W ActivityManager: Spurious death for ProcessRecord{98f6597 0:com.test.thalitest/u0a77}, curProc for 5635: null
,11-22 17:34:15.411  3850  3850 W Binder_7: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[25224]" dev="sockfs" ino=25224 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 17:34:15.411  3850  3850 W Binder_7: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[25224]" dev="sockfs" ino=25224 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 17:34:15.418  3677  3677 I Keyboard.Facilitator: onFinishInput()
,11-22 17:34:15.488   929   952 I art     : Explicit concurrent mark sweep GC freed 133079(9MB) AllocSpace objects, 87(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.991ms total 110.783ms
,11-22 17:34:15.502  3991  6044 I MicroRecognitionRnrImpl: Starting detection.
,11-22 17:34:15.503  3991  6045 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d8651ca
,11-22 17:34:15.507   512  6047 I AudioFlinger: AudioFlinger's thread 0xf1fc0000 ready to run
,11-22 17:34:15.508   512  3027 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 17:34:15.508   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-22 17:34:15.509  3991  6045 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d8651ca
11-22 17:34:15.511  6028  6028 I art     : System.exit called, status: 0
11-22 17:34:15.511  6028  6028 I AndroidRuntime: VM exiting with result code 0.
,11-22 17:34:15.520   512  6047 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-22 17:34:15.520   512  6047 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-22 17:34:15.520   512  6047 I ACDB-LOADER: ACDB AFE returned = -19
11-22 17:34:15.520   512  6047 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-22 17:34:15.520   512  6047 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-22 17:34:15.520   512  6047 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-22 17:34:15.527   929   952 I ActivityManager: Start proc 6049:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-22 17:34:15.527   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
11-22 17:34:15.528   512  6047 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-22 17:34:15.535  3677  3677 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-22 17:34:15.538  5903  5903 D BluetoothMapAppObserver: onReceive
,11-22 17:34:15.538  5903  5903 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-22 17:34:15.539   929  2955 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-22 17:34:15.540  4057  4205 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-22 17:34:15.557  3677  6061 I Keyboard.Facilitator.DecoderInitializer: run()
,11-22 17:34:15.562  3677  6061 I Decoder : createOrResetDecoder
,11-22 17:34:15.576  3418  6066 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-22 17:34:15.608  3797  3797 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-22 17:34:15.615  3597  3597 I ConfigService: onCreate
,11-22 17:34:15.616  3991  3991 I HotwordWorkerImpl: onReady
,11-22 17:34:15.611   391   391 W kworker/3:2: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 17:34:15.621   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-22 17:34:15.615   391   391 W kworker/3:2: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 17:34:15.621   391   391 W kworker/3:2: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 17:34:15.635  3819  3931 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-22 17:34:15.635   929   941 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
11-22 17:34:15.636   929   941 E PackageManager: Failed to write settings, restoring backup
11-22 17:34:15.636   929   941 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-22 17:34:15.636   929   941 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-22 17:34:15.636   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-22 17:34:15.636   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-22 17:34:15.636   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-22 17:34:15.636   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:34:15.636   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:34:15.636   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 17:34:15.639   929   942 E DropBoxManagerService: Can't write: system_server_wtf
11-22 17:34:15.639   929   942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-22 17:34:15.639   929   942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 17:34:15.639   929   942 E DropBoxManagerService: 	... 13 more
11-22 17:34:15.639  3677  6061 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-22 17:34:15.646  3418  6066 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-22 17:34:15.647   929   940 I ActivityManager: Start proc 6071:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-22 17:34:15.648  3819  3931 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-22 17:34:15.648  3819  3931 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3819
11-22 17:34:15.648  3819  3931 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDa,tabase.java:1499)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:34:15.648  3819  3931 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 17:34:15.652   929   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-22 17:34:15.653   929  6077 E DropBoxManagerService: Can't write: system_app_crash
11-22 17:34:15.653   929  6077 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 17:34:15.653   929  6077 E DropBoxManagerService: 	... 5 more
,11-22 17:34:15.657  3991  5625 W SearchService: Abort, client detached.
,11-22 17:34:15.661  3991  3991 I HotwordDetector: Closing mic
11-22 17:34:15.661  3991  4225 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d8651ca
11-22 17:34:15.662  3991  6045 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-22 17:34:15.663  3418  6066 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-22 17:34:15.663  3418  6066 E AndroidRuntime: Process: android.process.acore, PID: 3418
11-22 17:34:15.663  3418  6066 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:34:15.663  3418  6066 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-22 17:34:15.661   725   725 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[35931]" dev="sockfs" ino=35931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 17:34:15.661   725   725 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35931]" dev="sockfs" ino=35931 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 17:34:15.661   726   726 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33564]" dev="sockfs" ino=33564 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 17:34:15.661   726   726 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33564]" dev="sockfs" ino=33564 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 17:34:15.667   929  6084 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 17:34:15.676   929  6085 E DropBoxManagerService: Can't write: system_app_crash
11-22 17:34:15.676   929  6085 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 17:34:15.676   929  6085 E DropBoxManagerService: 	... 5 more
,11-22 17:34:15.682  3597  3597 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-22 17:34:15.682  3597  3597 D AndroidRuntime: Shutting down VM
11-22 17:34:15.683  3597  3597 E AndroidRuntime: FATAL EXCEPTION: main
11-22 17:34:15.683  3597  3597 E AndroidRuntime: Process: com.google.process.gapps, PID: 3597
11-22 17:34:15.683  3597  3597 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-22 17:34:15.683  3597  3597 E AndroidRuntime: 	... 8 more
11-22 17:34:15.686   929  6087 E DropBoxManagerService: Can't write: system_app_crash
11-22 17:34:15.686   929  6087 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at libcore.,io.Posix.open(Native Method)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 17:34:15.686   929  6087 E DropBoxManagerService: 	... 5 more
,11-22 17:34:15.725   512  6047 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-22 17:34:15.726   512  6047 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-22 17:34:15.729   512  6047 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-22 17:34:15.729   512  6047 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 17:34:15.730   512  3027 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 17:34:15.732  3991  6044 I MicroRecognitionRnrImpl: Detection finished
11-22 17:34:15.732  3991  4229 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-22 17:34:15.809   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 17:34:16.006   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
