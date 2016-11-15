#### Test 923390502f71cd8_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-15 14:46:06.455  4016  4272 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
--------- beginning of system
11-15 14:46:06.510   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-15 14:46:06.537  4016  4272 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-15 14:46:06.961  5583  5583 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-15 14:46:06.967  5583  5583 D AndroidRuntime: CheckJNI is OFF
11-15 14:46:06.991  5583  5583 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-15 14:46:07.034  5583  5583 I Radio-JNI: register_android_hardware_Radio DONE
11-15 14:46:07.049  5583  5583 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-15 14:46:07.057   928  3763 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-15 14:46:07.074  5583  5583 D AndroidRuntime: Shutting down VM
11-15 14:46:07.082  4000  4015 W SearchService: Abort, client detached.
11-15 14:46:07.098  4000  4255 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@de659a2
11-15 14:46:07.098  4000  4000 I HotwordDetector: Closing mic
11-15 14:46:07.098  4000  4267 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-15 14:46:07.111   928  3436 I ActivityManager: Start proc 5592:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-15 14:46:07.167   512  4269 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-15 14:46:07.169   512  4269 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-15 14:46:07.172   512  4269 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-15 14:46:07.172   512  4269 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-15 14:46:07.173   512  3047 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-15 14:46:07.174  4000  4257 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-15 14:46:07.174  4000  4266 I MicroRecognitionRnrImpl: Detection finished
11-15 14:46:07.209  5592  5592 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-15 14:46:07.229  5592  5592 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-15 14:46:07.293  5592  5592 I LibraryLoader: Time to load native libraries: 60 ms (timestamps 3963-4023)
11-15 14:46:07.293  5592  5592 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-15 14:46:07.325  5592  5592 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e604e3e}
,11-15 14:46:07.326  5592  5592 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-15 14:46:07.326  5592  5592 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-15 14:46:07.332  5592  5592 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-15 14:46:07.333  5592  5592 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-15 14:46:07.390  5592  5592 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-15 14:46:07.403  5592  5592 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-15 14:46:07.404  5592  5592 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-15 14:46:07.404  5592  5592 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-15 14:46:07.404  5592  5592 I Adreno  : Build Date                       : 12/06/15
11-15 14:46:07.404  5592  5592 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-15 14:46:07.404  5592  5592 I Adreno  : Local Branch                     : mybranch17112971
11-15 14:46:07.404  5592  5592 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-15 14:46:07.404  5592  5592 I Adreno  : Remote Branch                    : NONE
11-15 14:46:07.404  5592  5592 I Adreno  : Reconstruct Branch               : NOTHING
,11-15 14:46:07.468   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9dd7491:true
,11-15 14:46:07.502   951   951 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[33804]" dev="sockfs" ino=33804 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:07.502   951   951 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33804]" dev="sockfs" ino=33804 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:07.515  5592  5592 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-15 14:46:07.523  5592  5592 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-15 14:46:07.552   407   407 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31619]" dev="sockfs" ino=31619 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:07.552   407   407 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31619]" dev="sockfs" ino=31619 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:07.554  5592  5629 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-15 14:46:07.555  3169  3169 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33807]" dev="sockfs" ino=33807 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:07.555  3169  3169 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33807]" dev="sockfs" ino=33807 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:07.559  5592  5616 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-15 14:46:07.580  5592  5629 I OpenGLRenderer: Initialized EGL, version 1.4
,11-15 14:46:07.655  3437  3437 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31623]" dev="sockfs" ino=31623 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:07.655  3437  3437 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31623]" dev="sockfs" ino=31623 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:07.658   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +571ms
,11-15 14:46:07.658   939   939 W Binder_2: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31622]" dev="sockfs" ino=31622 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:07.658   939   939 W Binder_2: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31622]" dev="sockfs" ino=31622 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:07.663  3677  3677 I Keyboard.Facilitator: onFinishInput()
,11-15 14:46:07.689  5592  5592 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5592
,11-15 14:46:07.767  5592  5592 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-15 14:46:07.965  5592  5631 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -581699280
,11-15 14:46:07.969  5592  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-15 14:46:07.969  5592  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-15 14:46:07.969  5592  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-15 14:46:07.969  5592  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-15 14:46:07.969  5592  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-15 14:46:07.969  5592  5631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f7142d added. We now have 1 listener(s)
,11-15 14:46:07.972  5592  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-15 14:46:07.973  5592  5631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 14:46:07.973  5592  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:46:07.973  5592  5631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-15 14:46:07.975  5592  5631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f77b0 added. We now have 1 listener(s)
,11-15 14:46:07.976  5592  5631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:46:07.979   928  2996 D WifiService: New client listening to asynchronous messages
,11-15 14:46:07.981  5592  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:46:07.981  5592  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-15 14:46:07.981  5592  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-15 14:46:07.981  5592  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-15 14:46:07.981  5592  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-15 14:46:07.981  5592  5631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-15 14:46:07.981  5592  5631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-15 14:46:07.982  5592  5631 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-15 14:46:08.133  5592  5592 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-15 14:46:08.510  5592  5601 I art     : Background sticky concurrent mark sweep GC freed 77281(7MB) AllocSpace objects, 16(1476KB) LOS objects, 26% free, 24MB/32MB, paused 2.650ms total 282.220ms
,11-15 14:46:09.235  5592  5639 W jxcore-log: Initializing JXcore engine
,11-15 14:46:09.235  5592  5639 W jxcore-log: JXcore engine is ready
,11-15 14:46:09.258  5639  5639 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11697 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-15 14:46:09.258  5639  5639 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15471]" dev="sockfs" ino=15471 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-15 14:46:09.258  5639  5639 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-15 14:46:09.258  5639  5639 W Thread-57: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31589]" dev="sockfs" ino=31589 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-15 14:46:09.280  5592  5639 W jxcore-log: Starting JXcore engine
,11-15 14:46:09.332  5592  5639 W jxcore-log: Platform android
11-15 14:46:09.332  5592  5639 W jxcore-log: 
,11-15 14:46:09.332  5592  5639 W jxcore-log: Process ARCH arm
11-15 14:46:09.332  5592  5639 W jxcore-log: 
,11-15 14:46:09.479  5592  5639 I jxcore-log: JXcore Cordova bridge is ready!
11-15 14:46:09.479  5592  5639 I jxcore-log: 
,11-15 14:46:09.480  5592  5639 W jxcore-log: JXcore engine is started
,11-15 14:46:09.488  5592  5631 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-15 14:46:09.493  5592  5592 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-15 14:46:09.534   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 14:46:10.973  3601  3601 I ConfigService: onDestroy
,11-15 14:46:12.103   928  3437 I ActivityManager: Killing 5140:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-15 14:46:13.489   928  2986 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 14:46:15.587   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 14:46:16.986   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:17.132   928  2960 I ActivityManager: Killing 5229:org.codeaurora.ims/1001 (adj 15): empty #17
,11-15 14:46:17.279   928  2996 D WifiService: New client listening to asynchronous messages
,11-15 14:46:17.284  4000  5640 W CronetSyncConnectionRcs: Upload content type not set.
,11-15 14:46:17.987   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:18.988   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:19.103  5592  5639 I jxcore-log: 2016-11-15 13:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-15 14:46:19.103  5592  5639 I jxcore-log: 
,11-15 14:46:19.105  5592  5639 I jxcore-log: 2016-11-15 13:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-15 14:46:19.105  5592  5639 I jxcore-log: 
,11-15 14:46:19.112  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:46:19.112  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 14:46:19.113  5592  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 14:46:19.114  5592  5639 I jxcore-log: 2016-11-15 13:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-15 14:46:19.114  5592  5639 I jxcore-log: 
,11-15 14:46:19.115  5592  5639 I jxcore-log: 2016-11-15 13:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-15 14:46:19.115  5592  5639 I jxcore-log: 
,11-15 14:46:19.365  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:46:19.365  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1987b6e added. We now have 2 listener(s)
,11-15 14:46:19.365  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 14:46:19.366  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:46:19.366  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 14:46:19.366  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:46:19.366  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89c420f added. We now have 2 listener(s)
11-15 14:46:19.366  5592  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-15 14:46:19.367  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:46:19.368  5592  5639 D ExecuteNativeTests: Running unit tests
11-15 14:46:19.368  5592  5639 D BluetoothAdapter: enable(): BT is already enabled..!
11-15 14:46:19.369   928  3436 D WifiService: setWifiEnabled: true pid=5592, uid=10077
,11-15 14:46:19.369   928  3436 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:46:19.990   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:20.275  4883  4927 D Finsky  : [188] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-15 14:46:20.276  4883  4883 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-15 14:46:20.991   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:21.992   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-15 14:46:24.680   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 14:46:27.711   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-15 14:46:29.374  5592  5639 I com.test.thalitest.ThaliTestRunner: Running UT
,11-15 14:46:29.442  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-15 14:46:29.442  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9135d0 added. We now have 3 listener(s)
11-15 14:46:29.443  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:46:29.443  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-15 14:46:29.443  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:46:29.443  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:46:29.443  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71979c9 added. We now have 3 listener(s)
11-15 14:46:29.443  5592  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:46:29.445  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:46:29.450  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-15 14:46:29.450  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-15 14:46:29.450  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:29.450  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:29.450  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:29.451  5592  5639 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-15 14:46:29.452  5592  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 14:46:29.452  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 14:46:29.452  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:46:29.452  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:46:29.452  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:46:29.454  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-15 14:46:29.455  5592  5639 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-15 14:46:29.456  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-15 14:46:29.458  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-15 14:46:29.458  5592  5639 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-15 14:46:29.460  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 14:46:29.461  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:46:29.465  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 14:46:29.466  5592  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 14:46:29.466  5592  5639 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-15 14:46:29.467  5592  5639 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-15 14:46:29.467  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-15 14:46:29.467  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.467  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.467  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.467  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 14:46:29.467  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 14:46:29.467  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-15 14:46:29.467  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:29.468  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 14:46:29.468  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 14:46:29.469  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 14:46:29.469  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-15 14:46:29.469  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-15 14:46:29.469  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-15 14:46:29.469  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:29.469  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 14:46:29.469  5592  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 14:46:29.471  5592  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:46:29.472  5592  5592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:46:29.472  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 14:46:29.473  5592  5653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:46:29.473  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:46:29.473  5592  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:46:29.472  4905  4905 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33827]" dev="sockfs" ino=33827 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:29.472  4905  4905 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33827]" dev="sockfs" ino=33827 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:29.473  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 14:46:29.475  5592  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 14:46:29.476  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.476  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 14:46:29.477  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:46:29.477  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-15 14:46:29.477  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-15 14:46:29.478  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.478  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.478  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 14:46:29.478  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-15 14:46:29.478  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:46:29.479  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-15 14:46:29.479  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:29.479  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:29.479  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.479  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 14:46:29.479  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:29.479  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.479  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.480  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.480  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:29.483  4668  4683 D BtGatt.GattService: registerClient() - UUID=e151eb38-1474-43c7-a244-da9a660beb38
11-15 14:46:29.484  4668  4735 D BtGatt.GattService: onClientRegistered() - UUID=e151eb38-1474-43c7-a244-da9a660beb38, clientIf=5
11-15 14:46:29.484  5592  5602 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 14:46:29.487  4668  4737 D BtGatt.AdvertiseManager: message : 0
,11-15 14:46:29.490  4668  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 14:46:29.507  4668  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 14:46:29.515  4668  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 14:46:29.516  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.516  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.516  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 14:46:29.516  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.516  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.516  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.517  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.517  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.517  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:46:29.517  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:46:29.517  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.518  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:29.518  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.518  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:29.518  5592  5639 I io.jxcore.node.ConnectionHelper: start: OK
,11-15 14:46:29.519  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 14:46:29.519  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.519  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:29.519  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 14:46:29.519  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.520  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-15 14:46:29.520  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:29.520  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.520  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 14:46:29.520  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-15 14:46:29.520  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.521  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.521  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 14:46:29.521  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.524  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.525  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 14:46:29.525  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.525  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.525  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:29.525  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 14:46:30.022  5592  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-15 14:46:30.022  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-15 14:46:30.022  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-15 14:46:30.022  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-15 14:46:30.022  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-15 14:46:30.022  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-15 14:46:30.022  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-15 14:46:30.022  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-15 14:46:30.023  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-15 14:46:30.023  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-15 14:46:30.023  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-15 14:46:30.023  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-15 14:46:30.023  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-15 14:46:30.023  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-15 14:46:30.023  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-15 14:46:30.024  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-15 14:46:30.025  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-15 14:46:30.026  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-15 14:46:30.026  5592  5639 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 14:46:30.026  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-15 14:46:30.026  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 14:46:30.026  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 14:46:30.026  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 14:46:30.026  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 14:46:30.027  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 14:46:30.027  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 14:46:30.027  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 14:46:30.027  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 14:46:30.027  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:46:30.027  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:46:30.028  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 14:46:30.028  5592  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 14:46:30.028  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-15 14:46:30.028  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.028  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.028  5592  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 14:46:30.029  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.029  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.029  5592  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 14:46:30.030  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:30.031  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 14:46:30.033  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:30.033  5592  5639 D BluetoothLeScanner: could not find callback wrapper
11-15 14:46:30.033  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:46:30.033  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.033  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.033  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.034  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 14:46:30.034  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.035  4668  4737 D BtGatt.AdvertiseManager: message : 1
11-15 14:46:30.037  4668  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 14:46:30.050  4668  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 14:46:30.050  4668  4735 D BtGatt.GattService: Client app is not null!
,11-15 14:46:30.053  4668  4896 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 14:46:30.055  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 14:46:30.055  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.055  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 14:46:30.055  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.055  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.056  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.056  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-15 14:46:30.056  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-15 14:46:30.058  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:46:30.058  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.060  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.060  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:30.060  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.061  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.061  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:46:30.061  5592  5592 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 14:46:30.063  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 14:46:30.064  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:30.064  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:30.064  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 14:46:30.064  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:46:30.064  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:30.064  5592  5639 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 14:46:30.064  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.064  5592  5639 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 14:46:30.064  5592  5639 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-15 14:46:30.064  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:46:30.064  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-15 14:46:30.064  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 14:46:30.064  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.065  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.065  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 14:46:30.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.065  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.065  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 14:46:30.065  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 14:46:30.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 14:46:30.065  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:30.066  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.067  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.067  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.067  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.067  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:30.067  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 14:46:30.068  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 14:46:30.068  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 14:46:30.068  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 14:46:30.068  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 14:46:30.068  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 14:46:30.068  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:30.068  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 14:46:30.069  5592  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 14:46:30.069  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 14:46:30.071  5592  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:46:30.073  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:46:30.073  5592  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:46:30.073  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 14:46:30.074  5592  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 14:46:30.072  4896  4896 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31968]" dev="sockfs" ino=31968 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:30.072  4896  4896 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31968]" dev="sockfs" ino=31968 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:30.081  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.081  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 14:46:30.082  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:46:30.083  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:46:30.083  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-15 14:46:30.085  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.085  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.086  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 14:46:30.086  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 14:46:30.086  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:46:30.086  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-15 14:46:30.086  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:30.086  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:30.086  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.086  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 14:46:30.087  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:30.087  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.087  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.087  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.088  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:30.090  4668  4685 D BtGatt.GattService: registerClient() - UUID=e039575d-a0d1-4ec8-83a5-7881b0436a6e
11-15 14:46:30.091  4668  4735 D BtGatt.GattService: onClientRegistered() - UUID=e039575d-a0d1-4ec8-83a5-7881b0436a6e, clientIf=5
11-15 14:46:30.091  5592  5602 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 14:46:30.093  4668  4737 D BtGatt.AdvertiseManager: message : 0
11-15 14:46:30.095  4668  4737 D BtGatt.AdvertiseManager: starting multi advertising
11-15 14:46:30.109  4668  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 14:46:30.116  4668  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-15 14:46:30.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 14:46:30.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:46:30.120  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:46:30.120  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.122  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.122  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.122  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.122  5592  5639 I io.jxcore.node.ConnectionHelper: start: OK
11-15 14:46:30.122  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 14:46:30.122  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.123  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 14:46:30.124  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.127  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.127  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 14:46:30.128  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.128  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.128  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.128  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 14:46:30.627  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-15 14:46:30.627  5592  5639 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-15 14:46:30.627  5592  5639 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 14:46:30.627  5592  5639 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-15 14:46:30.627  5592  5639 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-15 14:46:30.628  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-15 14:46:30.628  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.628  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.628  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.629  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 14:46:30.631  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.631  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-15 14:46:30.632  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.633  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.633  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.636  4668  4737 D BtGatt.AdvertiseManager: message : 1
11-15 14:46:30.637  4668  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 14:46:30.651  4668  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 14:46:30.651  4668  4735 D BtGatt.GattService: Client app is not null!
,11-15 14:46:30.656  4668  4896 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 14:46:30.657  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 14:46:30.657  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.657  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 14:46:30.658  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.658  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.658  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.658  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 14:46:30.658  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.658  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.658  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.658  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 14:46:30.658  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 14:46:30.659  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 14:46:30.659  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-15 14:46:30.659  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 14:46:30.659  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 14:46:30.660  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.660  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 14:46:30.660  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 14:46:30.660  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.660  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.660  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.661  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:30.666  4668  4896 D BtGatt.GattService: registerClient() - UUID=b62c506d-f8b5-467c-bc0b-a3837c73ed16
11-15 14:46:30.667  4668  4735 D BtGatt.GattService: onClientRegistered() - UUID=b62c506d-f8b5-467c-bc0b-a3837c73ed16, clientIf=5
11-15 14:46:30.668  5592  5603 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 14:46:30.669  4668  4737 D BtGatt.AdvertiseManager: message : 0
,11-15 14:46:30.673  4668  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 14:46:30.690  4668  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 14:46:30.698  4668  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 14:46:30.699  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.700  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:46:30.700  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.700  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:46:30.701  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 14:46:30.701  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-15 14:46:30.701  5592  5639 I io.jxcore.node.ConnectionHelper: start: OK
,11-15 14:46:30.701  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.701  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:30.701  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 14:46:30.701  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-15 14:46:30.701  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.701  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:30.702  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 14:46:30.702  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 14:46:30.702  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 14:46:30.702  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.702  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.702  5592  5639 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-15 14:46:30.702  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-15 14:46:30.702  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-15 14:46:30.702  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 14:46:30.702  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 14:46:30.702  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-15 14:46:30.703  5592  5656 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 14:46:30.703  5592  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 14:46:30.703  5592  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 14:46:30.703  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-15 14:46:30.703  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:46:30.703  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.703  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.704  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:30.704  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-15 14:46:30.705  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:30.705  5592  5639 D BluetoothLeScanner: could not find callback wrapper
11-15 14:46:30.705  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:46:30.705  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.705  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.706  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.706  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 14:46:30.706  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.707  4668  4737 D BtGatt.AdvertiseManager: message : 1
11-15 14:46:30.707  4668  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 14:46:30.715  4668  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 14:46:30.715  4668  4735 D BtGatt.GattService: Client app is not null!
11-15 14:46:30.716  4668  4905 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 14:46:30.717  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-15 14:46:30.717  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.718  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 14:46:30.718  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.718  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.718  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.718  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 14:46:30.718  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 14:46:30.719  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:46:30.719  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.721  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.721  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:30.721  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.721  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.721  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:46:30.721  5592  5592 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 14:46:30.721  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 14:46:30.721  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:46:30.722  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:30.722  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:30.722  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-15 14:46:30.722  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.722  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:46:30.722  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 14:46:30.722  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.722  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.722  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 14:46:30.723  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.724  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-15 14:46:30.724  5592  5639 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-15 14:46:30.724  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.724  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.725  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.725  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.725  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 14:46:30.725  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-15 14:46:30.726  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 14:46:30.727  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-15 14:46:30.727  5592  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-15 14:46:30.728  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-15 14:46:30.728  5592  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-15 14:46:30.729  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-15 14:46:30.729  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 14:46:30.731  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:30.731  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:30.731  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:30.731  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 14:46:30.731  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:46:30.731  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:46:30.731  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:46:30.732  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-15 14:46:30.732  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-15 14:46:30.732  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:30.732  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-15 14:46:30.733  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-15 14:46:30.733  5592  5639 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-15 14:46:30.733  5592  5639 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-15 14:46:30.736  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-15 14:46:30.736  5592  5639 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-15 14:46:30.737  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-15 14:46:30.737  5592  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-15 14:46:30.738  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-15 14:46:30.738  5592  5639 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-15 14:46:30.738  5592  5639 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-15 14:46:30.738  5592  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-15 14:46:30.738  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 14:46:30.738  5592  5639 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-15 14:46:30.739  5592  5639 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-15 14:46:30.739  5592  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-15 14:46:30.739  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 14:46:30.739  5592  5639 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-15 14:46:30.739  5592  5639 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-15 14:46:30.739  5592  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-15 14:46:30.739  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 14:46:30.739  5592  5639 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-15 14:46:30.740  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-15 14:46:30.740  5592  5639 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-15 14:46:30.740  5592  5639 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-15 14:46:30.740  5592  5639 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-15 14:46:30.740  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,11-15 14:46:30.740  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.740  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.740  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.740  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 14:46:30.740  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 14:46:30.741  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 14:46:30.741  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 14:46:30.741  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 14:46:30.742  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 14:46:30.742  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 14:46:30.742  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 14:46:30.742  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 14:46:30.742  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 14:46:30.742  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 14:46:30.742  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:30.742  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-15 14:46:30.742  5592  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 14:46:30.743  5592  5660 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:46:30.745  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:46:30.745  5592  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:46:30.745  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-15 14:46:30.746  5592  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 14:46:30.742  4905  4905 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[29467]" dev="sockfs" ino=29467 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:30.742  4905  4905 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[29467]" dev="sockfs" ino=29467 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:30.749  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.750  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-15 14:46:30.750  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-15 14:46:30.750  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:46:30.750  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-15 14:46:30.753  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.753  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.753  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 14:46:30.753  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 14:46:30.753  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:46:30.753  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-15 14:46:30.754  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:30.754  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:30.754  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.754  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 14:46:30.754  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 14:46:30.754  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.754  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.754  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.755  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:30.757  4668  4685 D BtGatt.GattService: registerClient() - UUID=78d3a601-4db0-44db-9002-453a03f91ab7
11-15 14:46:30.758  4668  4735 D BtGatt.GattService: onClientRegistered() - UUID=78d3a601-4db0-44db-9002-453a03f91ab7, clientIf=5
11-15 14:46:30.758  5592  5603 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-15 14:46:30.759  4668  4737 D BtGatt.AdvertiseManager: message : 0
11-15 14:46:30.761  4668  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 14:46:30.772  4668  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 14:46:30.778  4668  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 14:46:30.779  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.779  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.779  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-15 14:46:30.779  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.779  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.779  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.779  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.779  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.779  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-15 14:46:30.781  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:46:30.781  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.782  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:30.782  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.782  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:30.782  5592  5639 I io.jxcore.node.ConnectionHelper: start: OK
11-15 14:46:30.782  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.783  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-15 14:46:30.783  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 14:46:30.783  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.786  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.786  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 14:46:30.786  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.786  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.786  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:30.786  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 14:46:31.284  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 14:46:31.284  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 14:46:31.285  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 14:46:31.285  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 14:46:31.285  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-15 14:46:31.285  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 14:46:31.285  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 14:46:31.286  5592  5660 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 14:46:31.286  5592  5660 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-15 14:46:31.286  5592  5660 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 14:46:31.286  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 14:46:31.286  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 14:46:31.287  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 14:46:31.287  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9135d0 removed from the list
,11-15 14:46:31.287  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:46:31.287  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 14:46:31.287  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:46:31.287  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 14:46:31.287  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:46:31.288  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 14:46:31.288  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.288  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:31.288  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.289  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.292  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:31.292  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-15 14:46:31.296  5592  5639 D BluetoothAdapter: STATE_ON
,11-15 14:46:31.296  5592  5639 D BluetoothLeScanner: could not find callback wrapper
11-15 14:46:31.296  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:46:31.297  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.297  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:31.297  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.298  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 14:46:31.298  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:31.300  4668  4737 D BtGatt.AdvertiseManager: message : 1
,11-15 14:46:31.302  4668  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 14:46:31.316  4668  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-15 14:46:31.316  4668  4735 D BtGatt.GattService: Client app is not null!
,11-15 14:46:31.317  4668  4683 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-15 14:46:31.318  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 14:46:31.319  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.319  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 14:46:31.319  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.319  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.319  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.319  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 14:46:31.319  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 14:46:31.321  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:46:31.321  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.323  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.323  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:31.324  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:31.324  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:31.324  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71979c9 removed from the list
11-15 14:46:31.324  5592  5639 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:46:31.324  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 14:46:31.324  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:31.324  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 14:46:31.325  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:31.325  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.325  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:46:31.325  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 14:46:31.325  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.325  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.325  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 14:46:31.325  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.330  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.330  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.330  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.330  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:31.330  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-15 14:46:31.831  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 14:46:36.334  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-15 14:46:36.337  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-15 14:46:36.337  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 14:46:36.337  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 14:46:36.343  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 14:46:36.345  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 14:46:36.345  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-15 14:46:36.345  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 14:46:36.345  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-15 14:46:36.345  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-15 14:46:36.345  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 14:46:36.346  5592  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 14:46:36.347  5592  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:46:36.348  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-15 14:46:36.350  5592  5639 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-15 14:46:36.350  5592  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-15 14:46:36.350  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-15 14:46:36.351  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-15 14:46:36.351  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-15 14:46:36.352  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-15 14:46:36.352  4683  4683 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33193]" dev="sockfs" ino=33193 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:36.357  5592  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 14:46:36.355  4683  4683 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33193]" dev="sockfs" ino=33193 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:36.362  5592  5639 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-15 14:46:36.363  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-15 14:46:36.363  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 14:46:36.363  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 14:46:36.363  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-15 14:46:36.364  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-15 14:46:36.364  5592  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 14:46:36.364  5592  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 14:46:36.364  5592  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 14:46:36.364  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 14:46:36.365  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:46:36.365  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-15 14:46:36.365  5592  5639 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9135d0 not in the list
11-15 14:46:36.365  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:46:36.365  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:46:36.365  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:46:36.365  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:46:36.365  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-15 14:46:36.365  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 14:46:36.365  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:36.368  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:36.368  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:36.368  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:36.368  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:36.368  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 14:46:36.368  5592  5639 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71979c9 not in the list
11-15 14:46:36.368  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:36.368  5592  5639 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:46:36.368  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:36.370  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-15 14:46:36.371  5592  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-15 14:46:36.371  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-15 14:46:36.372  5592  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-15 14:46:36.373  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-15 14:46:36.373  5592  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-15 14:46:36.373  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-15 14:46:36.374  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-15 14:46:36.374  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-15 14:46:36.375  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-15 14:46:36.375  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-15 14:46:36.375  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-15 14:46:36.376  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-15 14:46:36.376  5592  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-15 14:46:36.376  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 14:46:36.376  5592  5639 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-15 14:46:36.376  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-15 14:46:36.376  5592  5639 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-15 14:46:36.376  5592  5639 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-15 14:46:36.377  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-15 14:46:36.378  5592  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-15 14:46:36.378  5592  5639 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-15 14:46:36.378  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-15 14:46:36.379  5592  5639 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-15 14:46:36.379  5592  5639 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-15 14:46:36.379  5592  5639 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-15 14:46:36.379  5592  5639 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-15 14:46:36.379  5592  5639 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-15 14:46:36.380  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 14:46:36.380  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ffb6df added. We now have 3 listener(s)
11-15 14:46:36.382  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-15 14:46:36.382  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:46:36.382  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-15 14:46:36.382  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:46:36.383  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a12ff2c added. We now have 3 listener(s)
11-15 14:46:36.383  5592  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:46:36.383  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:46:36.386  5592  5639 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 14:46:36.386   928  3169 D WifiService: setWifiEnabled: true pid=5592, uid=10077
11-15 14:46:36.387   928  3169 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:46:36.388  5592  5639 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-15 14:46:36.392  5592  5639 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-15 14:46:36.392  5592  5639 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-15 14:46:36.395  5592  5639 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-15 14:46:36.395  5592  5639 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-15 14:46:36.400  4668  4731 D BluetoothAdapterState: Current state: ON, message: 23
,11-15 14:46:36.400  4668  4731 D BluetoothAdapterProperties: Setting state to 13
11-15 14:46:36.400  4668  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:46:36.401  5592  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-15 14:46:36.401  4668  4731 D BluetoothAdapterProperties: onBluetoothDisable()
,11-15 14:46:36.401  5592  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:46:36.402  5592  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-15 14:46:36.402  4668  4731 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:46:36.404  4668  4668 D BluetoothMapService: onReceive
,11-15 14:46:36.404  4668  4668 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 14:46:36.404  4668  4668 D BluetoothMapService: STATE_TURNING_OFF
11-15 14:46:36.407  4668  4735 D BluetoothAdapterProperties: Scan Mode:20
11-15 14:46:36.408  4668  4668 D BluetoothMapService: MAP Service closeService in
11-15 14:46:36.408  4668  4668 D BluetoothMapMasInstance0: MAP Service shutdown
11-15 14:46:36.408  4668  4668 D ObexServerSockets0: shutdown(block = true)
11-15 14:46:36.409  5268  5268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 14:46:36.409  4668  4668 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 14:46:36.409  4668  4907 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-15 14:46:36.409  4668  4668 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-15 14:46:36.409  4668  4908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-15 14:46:36.410  4668  4889 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-15 14:46:36.410  4668  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-15 14:46:36.416  5268  5268 D DockEventReceiver: finishStartingService: stopping service
,11-15 14:46:36.417  4668  4668 I BtOppRfcommListener: stopping Accept Thread
11-15 14:46:36.417  4668  5288 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-15 14:46:36.417  4668  5288 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-15 14:46:36.420   928  3809 I ActivityManager: Killing 5047:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-15 14:46:36.453  4668  4668 D HeadsetService: Received stop request...Stopping profile...
11-15 14:46:36.455  3794  3834 D BluetoothHeadset: Proxy object disconnected
,11-15 14:46:36.455   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 14:46:36.455   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 14:46:36.455   928   928 D BluetoothHeadset: Proxy object disconnected
11-15 14:46:36.455  5268  5278 D BluetoothHeadset: Proxy object disconnected
11-15 14:46:36.456  3151  3953 D BluetoothHeadset: Proxy object disconnected
11-15 14:46:36.456  3151  3151 D HeadsetProfile: Bluetooth service disconnected
11-15 14:46:36.457  5268  5268 D HeadsetProfile: Bluetooth service disconnected
,11-15 14:46:36.458  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 14:46:36.458  4668  4668 D A2dpService: Received stop request...Stopping profile...
,11-15 14:46:36.458  4668  4900 D A2dpStateMachine: Exit Disconnected: -1
,11-15 14:46:36.460   928   928 D BluetoothA2dp: Proxy object disconnected
11-15 14:46:36.460  5268  5268 D BluetoothA2dp: Proxy object disconnected
,11-15 14:46:36.461  4668  4668 D HidService: Received stop request...Stopping profile...
11-15 14:46:36.461  4668  4668 D HidService: Stopping Bluetooth HidService
,11-15 14:46:36.461  3151  3151 D BluetoothA2dp: Proxy object disconnected
11-15 14:46:36.461  3151  3151 D BluetoothInputDevice: Proxy object disconnected
11-15 14:46:36.461  3151  3151 D HidProfile: Bluetooth service disconnected
11-15 14:46:36.462  4668  4668 D HealthService: Received stop request...Stopping profile...
11-15 14:46:36.463  4668  4668 D PanService: Received stop request...Stopping profile...
11-15 14:46:36.464  3151  3151 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 14:46:36.464  3151  3151 D PanProfile: Bluetooth service disconnected
11-15 14:46:36.464  5268  5268 D BluetoothInputDevice: Proxy object disconnected
11-15 14:46:36.464  5268  5268 D HidProfile: Bluetooth service disconnected
11-15 14:46:36.464  5268  5268 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-15 14:46:36.464  5268  5268 D PanProfile: Bluetooth service disconnected
11-15 14:46:36.465  4668  4668 D BluetoothMapService: Received stop request...Stopping profile...
,11-15 14:46:36.465  4668  4668 D BluetoothMapService: stop()
11-15 14:46:36.466  4668  4668 D BluetoothMapAppObserver: deinitObservers()
11-15 14:46:36.466  4668  4668 D BluetoothMapAppObserver: removeReceiver()
11-15 14:46:36.467  5268  5268 D BluetoothMap: Proxy object disconnected
11-15 14:46:36.467  5268  5268 D MapProfile: Bluetooth service disconnected
,11-15 14:46:36.468  3151  3151 D BluetoothMap: Proxy object disconnected
11-15 14:46:36.468  3151  3151 D MapProfile: Bluetooth service disconnected
,11-15 14:46:36.468  4668  4668 V BluetoothAdapterState: isTurningOff()=true
,11-15 14:46:36.468  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:36.468  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:36.468  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:36.469  4668  4668 D SapService: Received stop request...Stopping profile...
11-15 14:46:36.469  4668  4668 V SapService: stop()
11-15 14:46:36.471  4668  4668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-15 14:46:36.471  4668  4668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-15 14:46:36.471  4668  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:46:36.471  4668  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:46:36.471  4668  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:46:36.472  4668  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-15 14:46:36.472  4668  4735 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-15 14:46:36.473  3151  3151 D BluetoothPbap: Proxy object disconnected
11-15 14:46:36.473  3151  3151 D PbapServerProfile: Bluetooth service disconnected
11-15 14:46:36.473  5268  5268 D BluetoothPbap: Proxy object disconnected
11-15 14:46:36.473  5268  5268 D PbapServerProfile: Bluetooth service disconnected
11-15 14:46:36.474  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-15 14:46:36.474  4668  4668 V BluetoothAdapterState: isTurningOn()=false
,11-15 14:46:36.474  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:36.474  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:36.475  4668  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-15 14:46:36.475  4668  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:46:36.475  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-15 14:46:36.475  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:36.475  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:36.475  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:46:36.475  4668  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-15 14:46:36.476  4668  4881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 14:46:36.476  4668  4668 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-15 14:46:36.476  4668  4881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-15 14:46:36.476  4668  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-15 14:46:36.476  4668  4881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-15 14:46:36.476  4668  4668 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-15 14:46:36.476  4668  4881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-15 14:46:36.476  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-15 14:46:36.476  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:36.476  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:36.476  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:36.476  4668  4668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-15 14:46:36.476  4668  4735 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-15 14:46:36.477  4668  4668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-15 14:46:36.477  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-15 14:46:36.477  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:36.477  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
,11-15 14:46:36.477  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:36.477  4668  4668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-15 14:46:36.478  4668  4668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-15 14:46:36.478  4668  4668 D BluetoothMapService: MAP Service closeService in
11-15 14:46:36.478  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-15 14:46:36.479  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:36.479  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:36.479  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:36.479  4668  4668 D BluetoothMapService: cleanup()
,11-15 14:46:36.479  4668  4668 D BluetoothMapService: MAP Service closeService in
11-15 14:46:36.479  4668  4668 V BluetoothAdapterState: isTurningOff()=true
11-15 14:46:36.479  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:36.479  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:36.479  4668  4668 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:36.479  4668  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-15 14:46:36.479  4668  4731 D BluetoothAdapterProperties: Setting state to 15
11-15 14:46:36.479  4668  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-15 14:46:36.480  4668  4731 I BluetoothAdapterState: Entering BleOnState
,11-15 14:46:36.489   928  3437 I ActivityManager: Start proc 5666:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-15 14:46:36.491  5268  5279 D BluetoothMap: onBluetoothStateChange: up=false
11-15 14:46:36.491  3794  4028 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:46:36.492  5268  5278 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 14:46:36.493   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:46:36.493  3151  3162 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:46:36.493  5268  5279 D BluetoothPan: onBluetoothStateChange on: false
11-15 14:46:36.494  5268  5278 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:46:36.494   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:46:36.495  5268  5279 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-15 14:46:36.495  3151  3953 D BluetoothPbap: onBluetoothStateChange: up=false
11-15 14:46:36.497  3151  3164 D BluetoothMap: onBluetoothStateChange: up=false
11-15 14:46:36.497  5268  5278 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:46:36.498  3151  3162 D BluetoothPan: onBluetoothStateChange on: false
11-15 14:46:36.498  3151  3953 D BluetoothA2dp: onBluetoothStateChange: up=false
11-15 14:46:36.499   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-15 14:46:36.499   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-15 14:46:36.499  3151  3164 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-15 14:46:36.500  4668  4731 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-15 14:46:36.500  4668  4731 D BluetoothAdapterProperties: Setting state to 16
11-15 14:46:36.500  4668  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-15 14:46:36.501  4668  4731 D BluetoothAdapterProperties: onBleDisable
11-15 14:46:36.501  4668  4731 I BluetoothAdapterState: Entering PendingCommandState
11-15 14:46:36.501  4668  4732 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-15 14:46:36.502  4668  4735 D BluetoothAdapterProperties: Scan Mode:20
,11-15 14:46:36.503  4668  4881 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-15 14:46:36.503  4668  4881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-15 14:46:36.537  5666  5666 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-15 14:46:36.709  4668  4735 I bt_hci  : shut_down
,11-15 14:46:36.714  4668  4739 D bt_hwcfg: hw_epilog_process
,11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-15 14:46:36.714  4668  4739 I bt_vendor: low_power_mode_cb
11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5,666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5,666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.k.d(PG:583)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.e.b(PG:170)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.File.exists(File.java:361)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 14:46:36.714  5666  5666 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-15 14:46:36.714  5666  5666 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-15 14:46:36.716  4668  4739 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-15 14:46:36.716  4668  4739 I bt_vendor: epilog_cb
11-15 14:46:36.716  4668  4739 I bt_hci  : epilog_finished_callback
11-15 14:46:36.720  4668  4735 I bt_hci_h4: hal_close
11-15 14:46:36.720  4668  4735 I bt_userial_vendor: device fd = 54 close
11-15 14:46:36.721  5268  5268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-15 14:46:36.727  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 14:46:36.737  5268  5268 D DockEventReceiver: finishStartingService: stopping service
11-15 14:46:36.738   928  3820 I ActivityManager: Killing 5388:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-15 14:46:36.826  4668  4732 D bt_stack_manager: event_shut_down_stack finished.
,11-15 14:46:36.826  4668  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-15 14:46:36.828  4668  4731 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-15 14:46:36.828  4668  4668 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-15 14:46:36.828  4668  4668 D BtGatt.GattService: Received stop request...Stopping profile...
,11-15 14:46:36.828  4668  4668 D BtGatt.GattService: stop()
11-15 14:46:36.828  4668  4668 D BtGatt.AdvertiseManager: advertise clients cleared
11-15 14:46:36.830  4668  4668 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:36.830  4668  4668 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:36.830  4668  4668 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:36.830  4668  4668 V BluetoothAdapterState: isBleTurningOff()=true
,11-15 14:46:36.830  4668  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-15 14:46:36.831  4668  4731 D BluetoothAdapterProperties: Setting state to 10
11-15 14:46:36.831  4668  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-15 14:46:36.831  4668  4731 I BluetoothAdapterState: Entering OffState
11-15 14:46:36.832   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-15 14:46:36.838  4668  4668 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-15 14:46:36.838  4668  4668 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-15 14:46:36.838  4668  4668 I BluetoothServiceJni: cleanupNative: return from cleanup
11-15 14:46:36.839  4668  4732 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-15 14:46:36.844  4668  4668 I art     : System.exit called, status: 0
,11-15 14:46:36.844  4668  4668 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-15 14:46:36.869  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 14:46:36.881   928  3172 I ActivityManager: Process com.android.bluetooth (pid 4668) has died
,11-15 14:46:36.892  5666  5695 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-15 14:46:36.903  5592  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:46:36.903  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 14:46:36.903  5592  5662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-15 14:46:36.903  5592  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 14:46:36.907  5592  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:46:36.917   928   945 I ActivityManager: Start proc 5697:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-15 14:46:36.959  5666  5681 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-15 14:46:36.966   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e58a8d:true
,11-15 14:46:36.977  5697  5697 D AdapterServiceConfig: Adding HeadsetService
,11-15 14:46:36.978  5697  5697 D AdapterServiceConfig: Adding A2dpService
11-15 14:46:36.978  5697  5697 D AdapterServiceConfig: Adding HidService
11-15 14:46:36.978  5697  5697 D AdapterServiceConfig: Adding HealthService
11-15 14:46:36.978  5697  5697 D AdapterServiceConfig: Adding PanService
11-15 14:46:36.978  5697  5697 D AdapterServiceConfig: Adding GattService
11-15 14:46:36.978  5697  5697 D AdapterServiceConfig: Adding BluetoothMapService
11-15 14:46:36.978  5697  5697 D AdapterServiceConfig: Adding SapService
,11-15 14:46:36.985   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51e7e45:true
11-15 14:46:36.986  5697  5697 D BluetoothAdapterState: make() - Creating AdapterState
,11-15 14:46:36.987  5697  5697 I bt_bluedroid: init
,11-15 14:46:36.988  5697  5710 I BluetoothAdapterState: Entering OffState
,11-15 14:46:36.989  5697  5711 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-15 14:46:36.990  5697  5711 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-15 14:46:36.990  5697  5711 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-15 14:46:36.990  5697  5711 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-15 14:46:36.991  5697  5697 I bt_bluedroid: get_profile_interface socket
,11-15 14:46:36.992  5697  5697 I bt_bluedroid: get_profile_interface sdp
11-15 14:46:36.992  5697  5715 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-15 14:46:36.993  5697  5715 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 14:46:36.995  5697  5708 I bt_bluedroid: config_hci_snoop_log
11-15 14:46:36.996   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-15 14:46:36.999  5697  5710 D BluetoothAdapterState: Current state: OFF, message: 0
,11-15 14:46:36.999  5697  5710 D BluetoothAdapterProperties: Setting state to 14
11-15 14:46:36.999  5697  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-15 14:46:37.001  5697  5710 D BluetoothBondStateMachine: make
,11-15 14:46:37.002  5697  5716 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-15 14:46:37.004  5697  5710 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:46:37.004  5697  5697 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-15 14:46:37.006  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
,11-15 14:46:37.006  5697  5697 D BtGatt.DebugUtils: handleDebugAction() action=null
11-15 14:46:37.007  5697  5697 D BtGatt.GattService: Received start request. Starting profile...
11-15 14:46:37.007  5697  5697 D BtGatt.GattService: start()
11-15 14:46:37.007  5697  5697 I bt_bluedroid: get_profile_interface gatt
,11-15 14:46:37.007  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
11-15 14:46:37.007  5697  5697 D BtGatt.AdvertiseManager: advertise manager created
,11-15 14:46:37.011  5697  5697 V BluetoothAdapterState: isTurningOff()=false
,11-15 14:46:37.011  5697  5697 V BluetoothAdapterState: isTurningOn()=false
11-15 14:46:37.011  5697  5697 V BluetoothAdapterState: isBleTurningOn()=true
11-15 14:46:37.011  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:46:37.011  5697  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-15 14:46:37.012  5697  5710 I bt_bluedroid: bt_bluedroid
11-15 14:46:37.012  5697  5711 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-15 14:46:37.012  5697  5711 I bt_hci  : start_up
,11-15 14:46:37.017  5697  5711 I bt_vendor: alloc value 0xf3f6b871
,11-15 14:46:37.017  5697  5711 I bt_vendor: init
11-15 14:46:37.017  5697  5711 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-15 14:46:37.017  5697  5711 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-15 14:46:37.126  5697  5711 D bt_hci  : start_up starting async portion
,11-15 14:46:37.126  5697  5719 I bt_hci  : event_finish_startup
11-15 14:46:37.126  5697  5719 I bt_hci_h4: hal_open
11-15 14:46:37.126  5697  5719 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-15 14:46:37.125  5720  5720 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-15 14:46:37.128  5697  5719 I bt_userial_vendor: device fd = 54 open
,11-15 14:46:37.140  5697  5719 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 14:46:37.142  5697  5719 D bt_hwcfg: Chipset BCM4358A3
,11-15 14:46:37.142  5697  5719 D bt_hwcfg: Target name = [BCM4358A3]
,11-15 14:46:37.142  5697  5719 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-15 14:46:37.409  5697  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-15 14:46:37.464  3601  5726 V NQFileLogger: [132] e.a: about to write to file
,11-15 14:46:37.467  3601  5726 V ProcessReports: [132] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-15 14:46:37.502  5697  5719 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-15 14:46:37.502  5697  5719 D bt_hwcfg: Settlement delay -- 100 ms
11-15 14:46:37.502  5697  5719 I bt_hwcfg: Setting fw settlement delay to 100 
,11-15 14:46:37.626  5697  5719 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-15 14:46:37.626  5697  5719 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-15 14:46:37.627  5697  5719 I bt_hwcfg: vendor lib fwcfg completed
11-15 14:46:37.627  5697  5719 I bt_vendor: firmware callback
11-15 14:46:37.627  5697  5719 I bt_hci  : firmware_config_callback
,11-15 14:46:37.631  5697  5728 I bt_btu  : btu_task pending for preload complete event
,11-15 14:46:37.631  5697  5728 I bt_btu_task: Bluetooth chip preload is complete
11-15 14:46:37.631  5697  5728 I bt_btu  : btu_task received preload complete event
,11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_HCI
,11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_AVDT
11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_AVRC
11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_A2D
11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_BNEP
11-15 14:46:37.634  5697  5728 I         : BTE_InitTraceLevels -- TRC_BTM
,11-15 14:46:37.635  5697  5728 I         : BTE_InitTraceLevels -- TRC_GAP
11-15 14:46:37.635  5697  5728 I         : BTE_InitTraceLevels -- TRC_PAN
11-15 14:46:37.635  5697  5728 I         : BTE_InitTraceLevels -- TRC_SDP
11-15 14:46:37.635  5697  5728 I         : BTE_InitTraceLevels -- TRC_GATT
11-15 14:46:37.635  5697  5728 I         : BTE_InitTraceLevels -- TRC_SMP
11-15 14:46:37.635  5697  5728 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-15 14:46:37.635  5697  5728 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-15 14:46:37.713  5697  5728 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ee9549
11-15 14:46:37.713  5697  5728 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ee9549 
,11-15 14:46:37.734  5697  5715 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
11-15 14:46:37.734  5697  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-15 14:46:37.735  5697  5715 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-15 14:46:37.737  5697  5715 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-15 14:46:37.739  5697  5715 D BluetoothAdapterProperties: Scan Mode:20
11-15 14:46:37.739  5697  5715 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-15 14:46:37.740  5697  5715 D bt_hci  : do_postload posting postload work item
,11-15 14:46:37.740  5697  5719 I bt_hci  : event_postload
,11-15 14:46:37.740  5697  5719 I bt_vendor: sco_config_cb
11-15 14:46:37.740  5697  5719 I bt_hci  : sco_config_callback postload finished.
11-15 14:46:37.743  5697  5715 D bt_bte_conf: Device ID record 1 : primary
11-15 14:46:37.743  5697  5715 D bt_bte_conf:   vendorId            = 000f
11-15 14:46:37.743  5697  5715 D bt_bte_conf:   vendorIdSource      = 0001
11-15 14:46:37.743  5697  5715 D bt_bte_conf:   product             = 1200
11-15 14:46:37.743  5697  5715 D bt_bte_conf:   version             = 1436
11-15 14:46:37.743  5697  5715 D bt_bte_conf:   clientExecutableURL = 
11-15 14:46:37.743  5697  5715 D bt_bte_conf:   serviceDescription  = 
,11-15 14:46:37.744  5697  5715 D bt_bte_conf:   documentationURL    = 
11-15 14:46:37.744  5697  5715 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-15 14:46:37.744  5697  5711 D bt_stack_manager: event_start_up_stack finished
,11-15 14:46:37.745  5697  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-15 14:46:37.745  5697  5710 D BluetoothAdapterProperties: Setting state to 15
11-15 14:46:37.745  5697  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-15 14:46:37.745  5697  5719 I bt_vendor: low_power_mode_cb
11-15 14:46:37.747  5697  5710 I BluetoothAdapterState: Entering BleOnState
,11-15 14:46:37.751  5697  5710 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-15 14:46:37.751  5697  5710 D BluetoothAdapterProperties: Setting state to 11
11-15 14:46:37.751  5697  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-15 14:46:37.756  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
11-15 14:46:37.757  5697  5697 D HeadsetService: Received start request. Starting profile...
,11-15 14:46:37.760  5697  5697 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-15 14:46:37.760  5697  5697 D HeadsetStateMachine: make
,11-15 14:46:37.769  5697  5710 I BluetoothAdapterState: Entering PendingCommandState
,11-15 14:46:37.769  5697  5697 D HeadsetStateMachine: max_hf_connections = 1
,11-15 14:46:37.770  5697  5697 I bt_bluedroid: get_profile_interface handsfree
,11-15 14:46:37.770  5697  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-15 14:46:37.770  5697  5715 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-15 14:46:37.773  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
,11-15 14:46:37.774  5697  5697 D A2dpService: Received start request. Starting profile...
11-15 14:46:37.775  5697  5697 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-15 14:46:37.776  5697  5697 I bt_bluedroid: get_profile_interface avrcp
,11-15 14:46:37.782  5697  5697 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-15 14:46:37.782  5697  5697 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-15 14:46:37.782  5697  5697 D A2dpStateMachine: make
11-15 14:46:37.783  5697  5697 I bt_bluedroid: get_profile_interface a2dp
,11-15 14:46:37.785  5697  5735 D A2dpStateMachine: Enter Disconnected: -2
,11-15 14:46:37.785  5697  5697 I BluetoothHidServiceJni: classInitNative: succeeds
,11-15 14:46:37.786  5697  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-15 14:46:37.786  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
,11-15 14:46:37.787  5697  5697 D HidService: Received start request. Starting profile...
11-15 14:46:37.787  5697  5697 I bt_bluedroid: get_profile_interface hidhost
11-15 14:46:37.787  5697  5697 D HidService: setHidService(): set to: null
11-15 14:46:37.787  5697  5715 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3eca56d
11-15 14:46:37.787  5697  5715 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-15 14:46:37.789  5697  5697 I BluetoothHealthServiceJni: classInitNative: succeeds
11-15 14:46:37.790  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
11-15 14:46:37.790  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-15 14:46:37.790  5697  5697 D HealthService: Received start request. Starting profile...
,11-15 14:46:37.792  5697  5697 I bt_bluedroid: get_profile_interface health
11-15 14:46:37.793  5697  5697 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-15 14:46:37.793  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
,11-15 14:46:37.794  5697  5697 D PanService: Received start request. Starting profile...
,11-15 14:46:37.794  5697  5697 D BluetoothPanServiceJni: initializeNative(L110): pan
11-15 14:46:37.794  5697  5697 I bt_bluedroid: get_profile_interface pan
11-15 14:46:37.795  5697  5715 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-15 14:46:37.798  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
,11-15 14:46:37.798  5697  5697 D BluetoothMapService: Received start request. Starting profile...
,11-15 14:46:37.799  5697  5697 D BluetoothMapService: start()
11-15 14:46:37.801  5697  5697 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-15 14:46:37.802  5697  5697 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-15 14:46:37.802  5697  5697 D BluetoothMapAppObserver: createReceiver()
11-15 14:46:37.803  5697  5697 D BluetoothMapAppObserver: initObservers()
11-15 14:46:37.803  5697  5697 D BluetoothMapAppObserver: getEnabledAccountItems()
11-15 14:46:37.808  5697  5697 V SapService: SapBinder()
11-15 14:46:37.808  5697  5697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
11-15 14:46:37.809  5697  5697 D SapService: Received start request. Starting profile...
11-15 14:46:37.809  5697  5697 V SapService: start()
11-15 14:46:37.811  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:37.811  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-15 14:46:37.811  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:37.811  5697  5733 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-15 14:46:37.811  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:37.812  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
,11-15 14:46:37.813  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:37.813  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-15 14:46:37.813  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:37.813  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:37.813  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:37.813  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-15 14:46:37.814  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:37.814  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:37.814  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:37.814  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-15 14:46:37.814  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:37.814  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:37.815  5697  5697 V BluetoothAdapterState: isTurningOff()=false
11-15 14:46:37.815  5697  5697 V BluetoothAdapterState: isTurningOn()=true
11-15 14:46:37.815  5697  5697 V BluetoothAdapterState: isBleTurningOn()=false
11-15 14:46:37.815  5697  5697 V BluetoothAdapterState: isBleTurningOff()=false
11-15 14:46:37.815  5697  5710 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-15 14:46:37.815  5697  5710 D BluetoothAdapterProperties: ScanMode =  20
11-15 14:46:37.815  5697  5710 D BluetoothAdapterProperties: State =  11
11-15 14:46:37.816  5697  5715 D BluetoothAdapterProperties: Scan Mode:21
11-15 14:46:37.816  5697  5710 D BluetoothAdapterProperties: Setting state to 12
11-15 14:46:37.817  5697  5710 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-15 14:46:37.817  5697  5715 D BluetoothAdapterProperties: Discoverable Timeout:120
11-15 14:46:37.817  5697  5710 I BluetoothAdapterState: Entering OnState
11-15 14:46:37.817  5268  5278 D BluetoothMap: onBluetoothStateChange: up=true
11-15 14:46:37.819  3794  3834 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:46:37.820  5268  5278 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 14:46:37.821   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:46:37.821  3151  3164 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:46:37.821  5268  5279 D BluetoothPan: onBluetoothStateChange on: true
11-15 14:46:37.823  5268  5278 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:46:37.823  5268  5268 D BluetoothMap: Proxy object connected
11-15 14:46:37.823   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 14:46:37.823  5268  5268 D MapProfile: Bluetooth service connected
11-15 14:46:37.823  5268  5268 D BluetoothMap: getConnectedDevices()
11-15 14:46:37.824  5268  5279 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 14:46:37.824   928   928 D BluetoothA2dp: Proxy object connected
11-15 14:46:37.826  3151  3953 D BluetoothPbap: onBluetoothStateChange: up=true
11-15 14:46:37.827  5697  5697 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-15 14:46:37.827  5697  5697 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-15 14:46:37.829  5697  5697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:46:37.829  3151  3162 D BluetoothMap: onBluetoothStateChange: up=true
11-15 14:46:37.830  5697  5697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:46:37.830  3151  3151 D BluetoothMap: Proxy object connected
11-15 14:46:37.830  5268  5279 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 14:46:37.830  3151  3151 D MapProfile: Bluetooth service connected
11-15 14:46:37.830  3151  3151 D BluetoothMap: getConnectedDevices()
11-15 14:46:37.832  5697  5697 D ObexServerSockets: Succeed to create listening sockets 
11-15 14:46:37.832  3151  3953 D BluetoothPan: onBluetoothStateChange on: true
11-15 14:46:37.832  5697  5697 D ObexServerSockets0: startAccept()
11-15 14:46:37.832  5697  5697 D ObexServerSockets0: prepareForNewConnect()
11-15 14:46:37.834  5268  5268 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 14:46:37.834  3151  3151 D BluetoothPan: BluetoothPAN Proxy object connected
11-15 14:46:37.834  5268  5268 D PanProfile: Bluetooth service connected
11-15 14:46:37.834  3151  3151 D PanProfile: Bluetooth service connected
11-15 14:46:37.834  5268  5268 D BluetoothInputDevice: Proxy object connected
11-15 14:46:37.834  5268  5268 D HidProfile: Bluetooth service connected
11-15 14:46:37.834  5697  5697 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-15 14:46:37.834  5697  5697 D BluetoothSdpJni: SDP Create record success - handle: 0
11-15 14:46:37.834  3151  3164 D BluetoothA2dp: onBluetoothStateChange: up=true
11-15 14:46:37.835  5697  5741 D ObexServerSockets0: Accepting socket connection...
11-15 14:46:37.835  5268  5268 D BluetoothA2dp: Proxy object connected
11-15 14:46:37.835  5697  5742 D ObexServerSockets0: Accepting socket connection...
11-15 14:46:37.836   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:46:37.836   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-15 14:46:37.836  3151  3151 D BluetoothA2dp: Proxy object connected
11-15 14:46:37.836  3151  3162 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-15 14:46:37.838  3151  3151 D BluetoothInputDevice: Proxy object connected
11-15 14:46:37.839  3151  3151 D HidProfile: Bluetooth service connected
11-15 14:46:37.840   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-15 14:46:37.840  5697  5697 D BluetoothMapService: onReceive
11-15 14:46:37.840  5697  5697 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-15 14:46:37.841  5697  5697 D BluetoothMapService: STATE_ON
11-15 14:46:37.845  5697  5744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-15 14:46:37.846  5697  5744 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-15 14:46:37.846  5697  5744 D BluetoothSdpJni: SDP Create record success - handle: 1
11-15 14:46:37.848  5268  5268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-15 14:46:37.854  5268  5268 D DockEventReceiver: finishStartingService: stopping service
,11-15 14:46:37.855  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-15 14:46:37.862  5268  5268 D BluetoothPbap: Proxy object connected
,11-15 14:46:37.862  5268  5268 D PbapServerProfile: Bluetooth service connected
,11-15 14:46:37.865  3151  3151 D BluetoothPbap: Proxy object connected
11-15 14:46:37.865  3151  3151 D PbapServerProfile: Bluetooth service connected
,11-15 14:46:37.869  5697  5697 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-15 14:46:37.869  5697  5697 D ObexServerSockets0: prepareForNewConnect()
11-15 14:46:37.871  5697  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:46:37.889  5697  5752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:46:37.890  5697  5752 I BtOppRfcommListener: Accept thread started.
,11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-15 14:46:37.912  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-15 14:46:37.913  5592  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-15 14:46:37.914  5592  5639 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-15 14:46:37.915   928  3436 D WifiService: setWifiEnabled: false pid=5592, uid=10077
11-15 14:46:37.915   928  3436 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 14:46:37.917   928  2986 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-15 14:46:37.917  5592  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-15 14:46:37.917   928  2986 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-15 14:46:37.917   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 14:46:37.917   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 14:46:37.922  3794  4028 D BluetoothHeadset: Proxy object connected
,11-15 14:46:37.922   928   928 D BluetoothHeadset: Proxy object connected
11-15 14:46:37.922   928   928 D BluetoothHeadset: Proxy object connected
11-15 14:46:37.923   928   928 D BluetoothHeadset: Proxy object connected
11-15 14:46:37.923  5268  5278 D BluetoothHeadset: Proxy object connected
11-15 14:46:37.923  5268  5278 D BluetoothHeadset: Proxy object connected
,11-15 14:46:37.924  3151  3162 D BluetoothHeadset: Proxy object connected
,11-15 14:46:37.924  3151  3151 D HeadsetProfile: Bluetooth service connected
11-15 14:46:37.927  5268  5268 D HeadsetProfile: Bluetooth service connected
11-15 14:46:37.928   928  5361 D DhcpClient: Clearing IP address
11-15 14:46:37.928  5268  5268 D HeadsetProfile: Bluetooth service connected
11-15 14:46:37.928   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-15 14:46:37.931   507   920 D CommandListener: Setting iface cfg
,11-15 14:46:37.935  3601  5414 V NativeCrypto: Read error: ssl=0x7f691d7300: I/O error during system call, Connection timed out
,11-15 14:46:37.936   928   945 D BluetoothHeadset: Proxy object connected
,11-15 14:46:37.936   928   945 D BluetoothHeadset: Proxy object connected
,11-15 14:46:37.936  3601  5414 V NativeCrypto: SSL shutdown failed: ssl=0x7f691d7300: I/O error during system call, Broken pipe
,11-15 14:46:37.939   928  3820 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-15 14:46:37.939   928  5359 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-15 14:46:37.941   928  5359 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-15 14:46:37.942   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-15 14:46:37.942   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-15 14:46:37.942   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-15 14:46:37.943   928  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-15 14:46:37.943   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-15 14:46:37.946   928   928 D RttService: SCAN_AVAILABLE : 1
11-15 14:46:37.947   928  3105 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-15 14:46:37.948   533   533 E Parcel  : Reading a NULL string not supported here.
,11-15 14:46:37.949   928  2998 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-15 14:46:37.951  3754  3906 W QCNEJ   : |CORE| network lost: 100
11-15 14:46:37.952  3754  3906 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-15 14:46:37.953   928  5362 D DhcpClient: Receive thread stopped
,11-15 14:46:37.973   928  2986 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-15 14:46:37.974   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 14:46:37.987   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-15 14:46:37.994   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-15 14:46:37.994   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-15 14:46:37.994   507   920 D TetherController: Setting IP forward enable = 0
11-15 14:46:37.995   928  2998 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-15 14:46:37.995   928  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-15 14:46:37.998   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-15 14:46:38.001  5245  5245 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@df3170a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-15 14:46:38.002   928  2986 D DhcpClient: doQuit
11-15 14:46:38.002   928  2986 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-15 14:46:38.003  3463  3463 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-15 14:46:38.003  4000  4000 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-15 14:46:38.003   928  5361 D DhcpClient: onQuitting
,11-15 14:46:38.005  5033  5046 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-15 14:46:38.006  5033  5046 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 14:46:38.006  5033  5046 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-15 14:46:38.007  5033  5046 E SarControlService: no key has been found,reset the power
11-15 14:46:38.007  5033  5071 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 14:46:38.007  5033  5071 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 14:46:38.007  5033  5071 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 14:46:38.010  4016  4016 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-15 14:46:38.010  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 14:46:38.010  5059  5059 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-15 14:46:38.011  5033  5071 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-15 14:46:38.011  5033  5071 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 14:46:38.011  5033  5071 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 14:46:38.011  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 14:46:38.011  5059  5059 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-15 14:46:38.012  4016  4016 D SystemUpdateService: onCreate
11-15 14:46:38.014  5059  5073 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38601c0 HexData = [00000000ea03000000000000ffffffff]
,11-15 14:46:38.014  5059  5073 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 14:46:38.014  5059  5073 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-15 14:46:38.014  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 14:46:38.015  5033  5043 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 14:46:38.016  4016  4016 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-15 14:46:38.018  4016  5767 I SystemUpdateService: active receiver: enabled
,11-15 14:46:38.022  5059  5073 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38601c0 HexData = [00000000eb03000000000000ffffffff]
,11-15 14:46:38.022  5059  5073 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 14:46:38.022  5059  5073 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-15 14:46:38.023  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 14:46:38.023  5033  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-15 14:46:38.025  4016  5767 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 14:46:38.025  4016  4016 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-15 14:46:38.026  4016  5767 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-15 14:46:38.027  4016  5767 I SystemUpdateService: now status is 0 (complete)
,11-15 14:46:38.027  4016  5767 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 14:46:38.027  4016  5767 I SystemUpdateService: file has been verified
11-15 14:46:38.027  4016  5767 I SystemUpdateService: OTA package size = 21989297
11-15 14:46:38.027  4016  5386 I iu.UploadsManager: num queued entries: 0
11-15 14:46:38.027  3463  3463 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-15 14:46:38.027  4016  5386 I iu.UploadsManager: num updated entries: 0
11-15 14:46:38.028  4016  5386 I iu.SyncManager: NEXT; no task
,11-15 14:46:38.031  4016  5767 I SystemUpdateService: showing system update notification
,11-15 14:46:38.032  3463  3463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-15 14:46:38.040  4016  4016 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-15 14:46:38.042  4016  4016 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 14:46:38.046   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 14:46:38.053   928   938 I ActivityManager: Start proc 5774:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-15 14:46:38.054   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-15 14:46:38.055   507   920 D TetherController: Setting IP forward enable = 0
11-15 14:46:38.055   928  2998 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-15 14:46:38.055   928  2998 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-15 14:46:38.056  4016  4016 D SystemUpdateService: onDestroy
,11-15 14:46:38.058  3463  3463 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-15 14:46:38.063  3463  3463 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-15 14:46:38.098  5774  5774 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-15 14:46:38.100  5774  5774 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 14:46:38.106  5774  5774 D SprintDMHelper: simOperator: 
11-15 14:46:38.106  5774  5774 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 14:46:38.117  4471  5788 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-15 14:46:38.130   928  3820 I ActivityManager: Start proc 5789:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-15 14:46:38.160  5789  5789 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-15 14:46:38.167   928  3761 I ActivityManager: Killing 5245:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-15 14:46:38.186   928  2986 D wifi    : In wifi stop Hal
,11-15 14:46:38.186   928  2986 D wifi    : halHandle = 0x7f6788cf00, mVM = 0x7f83f0d140, mCls = 0x100a02
11-15 14:46:38.186   928  3462 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-15 14:46:38.187   928  3462 D WifiHAL : Got a signal to exit!!!
11-15 14:46:38.187   928  3462 I WifiHAL : Exit wifi_event_loop
11-15 14:46:38.187   928  2986 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-15 14:46:38.187   928  2986 E WifiHAL : Event processing terminated
,11-15 14:46:38.187   928  2986 D wifi    : In wifi cleaned up handler
11-15 14:46:38.187   928  2986 I WifiHAL : Internal cleanup completed
11-15 14:46:38.189  4471  4471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 14:46:38.190  3863  4238 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 14:46:38.209   928  3462 D wifi    : set interface wlan0 flags (DOWN)
,11-15 14:46:38.209   928  2986 D WifiNative-HAL: HAL event thread stopped successfully
,11-15 14:46:38.413   928   945 D Tethering: InitialState.processMessage what=4
,11-15 14:46:38.419   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:46:38.423  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 14:46:38.427  5592  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 14:46:38.429   928  3437 D WifiService: setWifiEnabled: true pid=5592, uid=10077
,11-15 14:46:38.429   928  3437 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 14:46:38.430  5592  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-15 14:46:38.432   507   920 D SoftapController: Softap fwReload - Ok
,11-15 14:46:38.434   507   920 D CommandListener: Setting iface cfg
,11-15 14:46:38.434   507   920 D CommandListener: Trying to bring down wlan0
11-15 14:46:38.435   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-15 14:46:38.437   928  2986 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-15 14:46:38.933   928  3437 D WifiService: setWifiEnabled: true pid=5592, uid=10077
,11-15 14:46:38.935   928  3437 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-15 14:46:39.050   928  2986 D wifi    : set interface wlan0 flags (UP)
,11-15 14:46:39.051   928  2986 I WifiHAL : Initializing wifi
,11-15 14:46:39.051   928  2986 I WifiHAL : Creating socket
,11-15 14:46:39.061   928  2986 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-15 14:46:39.061   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-15 14:46:39.061   928  2986 D wifi    : Did set static halHandle = 0x7f6788cf00
11-15 14:46:39.061   928  2986 D wifi    : halHandle = 0x7f6788cf00, mVM = 0x7f83f0d140, mCls = 0x201872
11-15 14:46:39.061   928  2986 D wifi    : array field set
,11-15 14:46:39.062   928  2986 I WifiNative-HAL: interface[0] = wlan0
,11-15 14:46:39.065   928  5805 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547197865728
,11-15 14:46:39.065   928  5805 D wifi    : waitForHalEvents called, vm = 0x7f83f0d140, obj = 0x201872, env = 0x7f6b62dd40
,11-15 14:46:39.144  5806  5806 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-15 14:46:39.168   928  2986 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-15 14:46:39.229  5806  5806 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-15 14:46:39.254  5806  5806 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-15 14:46:39.254  5806  5806 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-15 14:46:39.268   928  2986 D WifiConfigStore: Loading config and enabling all networks 
,11-15 14:46:39.287   928  2986 D WifiConfigStore: loaded 0 passpoint configs
,11-15 14:46:39.288   928  2986 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-15 14:46:39.288   928  2986 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-15 14:46:39.288   928  2986 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-15 14:46:39.289   928  2986 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-15 14:46:39.289   928  2986 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-15 14:46:39.290   928  2986 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-15 14:46:39.290   928  2986 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-15 14:46:39.290   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-15 14:46:39.290   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-15 14:46:39.290   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-15 14:46:39.290   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-15 14:46:39.290   928  2986 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-15 14:46:39.292   928  2986 D WifiNative-HAL: Setting external_sim to 1
,11-15 14:46:39.293   928  2986 D wifi    : setting dfs flag to true, 0x7f6cc3b920
11-15 14:46:39.293   928  2986 D WifiStateMachine: Setting OUI to DA-A1-19
11-15 14:46:39.293   928  2986 D wifi    : setting scan oui 0x7f6cc3b920
11-15 14:46:39.293   928  2986 D WifiHAL : Sending mac address OUI
,11-15 14:46:39.293  4471  4471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-15 14:46:39.296   928  2986 E native  : do suspend false
,11-15 14:46:39.302   928  2986 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-15 14:46:39.302   928   928 D RttService: SCAN_AVAILABLE : 3
,11-15 14:46:39.303   928  3105 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-15 14:46:39.306   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-15 14:46:39.308   507   920 D CommandListener: Setting iface cfg
,11-15 14:46:39.313   928  2969 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-15 14:46:39.314   928  2969 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-15 14:46:39.318   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106048 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-15 14:46:39.320   928  2969 D WifiNative-HAL: p2pGetDeviceAddress
,11-15 14:46:39.320   928  2969 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-15 14:46:39.445  5592  5662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-15 14:46:39.450  5592  5662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-15 14:46:39.453  5592  5639 D BluetoothAdapter: enable(): BT is already enabled..!
,11-15 14:46:39.454   928  3169 D WifiService: setWifiEnabled: true pid=5592, uid=10077
11-15 14:46:39.454   928  3169 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-15 14:46:39.456  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:46:39.456  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-15 14:46:39.456  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 14:46:39.457  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ffb6df removed from the list
11-15 14:46:39.457  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:46:39.457  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a12ff2c removed from the list
11-15 14:46:39.457  5592  5639 D io.jxcore.node.ConnectivityMonitor: stop
,11-15 14:46:39.462  5592  5639 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-15 14:46:39.465  5592  5639 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-15 14:46:39.466  5592  5639 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-15 14:46:39.469  5592  5639 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-15 14:46:39.472  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-15 14:46:39.473  5592  5639 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-15 14:46:39.475  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-15 14:46:39.475  5592  5639 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-15 14:46:39.476  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-15 14:46:39.479  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-15 14:46:39.479  5592  5639 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fe71a84 Bundle[{}]
11-15 14:46:39.480  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-15 14:46:39.480  5592  5639 I io.jxcore.node.LifeCycleMonitor: start: OK
11-15 14:46:39.480  5592  5639 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-15 14:46:39.481  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-15 14:46:39.481  5592  5639 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-15 14:46:39.481  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-15 14:46:39.481  5592  5639 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-15 14:46:39.482  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-15 14:46:39.482  5592  5639 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-15 14:46:39.482  5592  5639 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-15 14:46:39.483  5592  5639 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-15 14:46:39.485  5592  5639 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-15 14:46:39.487  5592  5639 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-15 14:46:39.488  5592  5639 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-15 14:46:39.489  5592  5639 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-15 14:46:39.489  5592  5639 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-15 14:46:39.490  5592  5639 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-15 14:46:39.492  5592  5639 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-15 14:46:39.493  5592  5639 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-15 14:46:39.494  5592  5639 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-15 14:46:39.495  5592  5639 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-15 14:46:39.496  5592  5639 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-15 14:46:39.497  5592  5639 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-15 14:46:39.497  5592  5639 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 137)
,11-15 14:46:39.498  5592  5639 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-15 14:46:39.498  5592  5639 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-15 14:46:39.498  5592  5639 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 138)
11-15 14:46:39.499  5592  5639 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-15 14:46:39.500  5592  5639 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-15 14:46:39.501  5592  5639 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-15 14:46:39.501  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-15 14:46:39.501  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ff378a added. We now have 3 listener(s)
11-15 14:46:39.503  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:46:39.503  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-15 14:46:39.503  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-15 14:46:39.503  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-15 14:46:39.503  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@252e1fb added. We now have 3 listener(s)
11-15 14:46:39.503  5592  5639 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-15 14:46:39.504  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-15 14:46:39.509  5592  5639 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-15 14:46:39.509  5592  5639 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-15 14:46:39.509  5592  5639 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-15 14:46:39.509  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,11-15 14:46:39.510  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.510  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.510  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.510  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-15 14:46:39.510  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 14:46:39.510  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 14:46:39.510  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:39.510  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-15 14:46:39.514  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-15 14:46:39.515  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-15 14:46:39.515  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-15 14:46:39.516  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 14:46:39.516  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 14:46:39.516  5592  5809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-15 14:46:39.516  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 14:46:39.516  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-15 14:46:39.516  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:39.516  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 14:46:39.517  5592  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:46:39.515  5707  5707 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[29573]" dev="sockfs" ino=29573 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:39.519  5592  5809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-15 14:46:39.515  5707  5707 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[29573]" dev="sockfs" ino=29573 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-15 14:46:39.520  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-15 14:46:39.520  5592  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-15 14:46:39.520  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 14:46:39.523  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:39.523  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 14:46:39.524  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:46:39.524  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:46:39.524  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-15 14:46:39.525  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.525  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:39.525  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 14:46:39.525  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 14:46:39.525  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:46:39.525  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-15 14:46:39.525  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:39.525  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 14:46:39.526  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.526  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 14:46:39.526  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:39.526  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.526  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.526  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.527  5592  5639 D BluetoothAdapter: STATE_ON
,11-15 14:46:39.529  5697  5707 D BtGatt.GattService: registerClient() - UUID=2bd006ea-8937-41e0-8071-96f4ac34173c
,11-15 14:46:39.530  5697  5715 D BtGatt.GattService: onClientRegistered() - UUID=2bd006ea-8937-41e0-8071-96f4ac34173c, clientIf=5
11-15 14:46:39.531  5592  5602 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-15 14:46:39.532  5697  5717 D BtGatt.AdvertiseManager: message : 0
,11-15 14:46:39.534  5697  5717 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 14:46:39.537  5697  5715 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-15 14:46:39.539  5697  5715 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-15 14:46:39.540  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.540  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.540  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 14:46:39.540  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.540  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.540  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.540  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.540  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.540  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:46:39.541  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:46:39.541  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.542  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.542  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.542  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:39.543  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [N,OT_STARTED]
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.543  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-15 14:46:39.544  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 14:46:39.546  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.546  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-15 14:46:39.546  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-15 14:46:39.546  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.546  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:39.546  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-15 14:46:40.047  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-15 14:46:40.047  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 14:46:40.048  5592  5592 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 14:46:42.415  5806  5806 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:46:42.420  5806  5806 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:46:42.426  5806  5806 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:46:42.431  5806  5806 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-15 14:46:42.451   928  3763 I ActivityManager: Killing 3940:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-15 14:46:42.471   928  2986 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-15 14:46:42.479   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-15 14:46:42.479   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 14:46:42.490   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-15 14:46:42.522   928  2986 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-15 14:46:42.527  5806  5806 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-15 14:46:42.951  5806  5806 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-15 14:46:42.982  5806  5806 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-15 14:46:42.984  5806  5806 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-15 14:46:42.995   928  2986 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 14:46:42.995   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 14:46:42.995   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-15 14:46:43.015   928  2986 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-15 14:46:43.028   507   920 D CommandListener: Setting iface cfg
,11-15 14:46:43.033   928  2986 D WifiStateMachine: Start Dhcp Watchdog 2
,11-15 14:46:43.040   928  5814 D DhcpClient: Receive thread started
,11-15 14:46:43.044   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:46:43.044   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-15 14:46:43.044   928  2998 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-15 14:46:43.046  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-15 14:46:43.046  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-15 14:46:43.046  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 14:46:43.046  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 14:46:43.046  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-15 14:46:43.046  5592  5809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 14:46:43.046  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-15 14:46:43.047  5592  5809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-15 14:46:43.047  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-15 14:46:43.047  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 14:46:43.047  5592  5809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-15 14:46:43.047  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-15 14:46:43.047  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-15 14:46:43.047  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-15 14:46:43.047  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 14:46:43.047  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 14:46:43.047  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:43.047  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.048  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:43.048  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:43.049  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:43.049  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 14:46:43.050  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:43.050  5592  5639 D BluetoothLeScanner: could not find callback wrapper
11-15 14:46:43.050  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:46:43.050  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.050  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.051  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.051  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 14:46:43.051  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.052  5697  5717 D BtGatt.AdvertiseManager: message : 1
11-15 14:46:43.053  5697  5717 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-15 14:46:43.063  5697  5715 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-15 14:46:43.063  5697  5715 D BtGatt.GattService: Client app is not null!
,11-15 14:46:43.064  5697  5707 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 14:46:43.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 14:46:43.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-15 14:46:43.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.065  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.066  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.066  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-15 14:46:43.066  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 14:46:43.067  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-15 14:46:43.067  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.069  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.069  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:43.069  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.069  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.070  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-15 14:46:43.070  5592  5592 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-15 14:46:43.070  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 14:46:43.070  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:46:43.070  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:43.070  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:43.070  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:43.071  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.071  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:46:43.071  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-15 14:46:43.071  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.071  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.071  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-15 14:46:43.071  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.073  5592  5592 ,D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.074  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.074  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.074  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.074  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:43.076  5592  5639 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-15 14:46:43.076  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:46:43.077  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:46:43.077  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-15 14:46:43.077  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-15 14:46:43.077  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-15 14:46:43.077  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-15 14:46:43.079  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-15 14:46:43.083  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:46:43.083  5592  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-15 14:46:43.083  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-15 14:46:43.088  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.088  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 14:46:43.089  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:46:43.089  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:46:43.089  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-15 14:46:43.093  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-15 14:46:43.096  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-15 14:46:43.097  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:43.097  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 14:46:43.097  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 14:46:43.097  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 14:46:43.098  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 14:46:43.098  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.099  5592  5639 D BluetoothAdapter: STATE_ON
,11-15 14:46:43.102  5697  5743 D BtGatt.GattService: registerClient() - UUID=b75fad0d-fdf5-42d8-a138-477c8d3adb56
11-15 14:46:43.102  5697  5715 D BtGatt.GattService: onClientRegistered() - UUID=b75fad0d-fdf5-42d8-a138-477c8d3adb56, clientIf=5
11-15 14:46:43.103  5592  5602 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-15 14:46:43.104  5697  5725 D BtGatt.GattService: start scan with filters
,11-15 14:46:43.108  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-15 14:46:43.108  5697  5718 D BtGatt.ScanManager: handling starting scan
11-15 14:46:43.108  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.108  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-15 14:46:43.109  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.109  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:46:43.109  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:43.110  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.110  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 14:46:43.110  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-15 14:46:43.110  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-15 14:46:43.110  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.110  5697  5718 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cc30431
11-15 14:46:43.110  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,11-15 14:46:43.111  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-15 14:46:43.112  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.114  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.114  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-15 14:46:43.115  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.115  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:43.115  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-15 14:46:43.117  5697  5715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-15 14:46:43.118  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:43.118  5697  5718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-15 14:46:43.119  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.119  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.119  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.119  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:43.119  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-15 14:46:43.125  5697  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-15 14:46:43.125  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:43.125  5697  5718 D BtGatt.ScanManager: Starting BLE batch scan
11-15 14:46:43.125  5697  5718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-15 14:46:43.126   928  2986 E native  : do suspend false
,11-15 14:46:43.133  5697  5715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-15 14:46:43.133  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:46:43.134   928  5813 D DhcpClient: Broadcasting DHCPDISCOVER
,11-15 14:46:43.138  5697  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-15 14:46:43.138  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:46:43.145   928  5814 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172730, domain null
,11-15 14:46:43.145   928  5813 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172730 seconds
,11-15 14:46:43.146   928  5813 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-15 14:46:43.232   928  5814 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-15 14:46:43.233   928  5813 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-15 14:46:43.235   507   920 D CommandListener: Setting iface cfg
11-15 14:46:43.240   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-15 14:46:43.245   928  5813 D DhcpClient: Scheduling renewal in 86399s
,11-15 14:46:43.256   928  2986 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-15 14:46:43.256   928  2986 D WifiConfigStore: No blacklist allowed without epno enabled
11-15 14:46:43.257   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-15 14:46:43.259   928  2998 D ConnectivityService: Adding iface wlan0 to network 101
,11-15 14:46:43.264   928  2986 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-15 14:46:43.307   928  2998 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-15 14:46:43.307   928  2998 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-15 14:46:43.310   928  2998 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-15 14:46:43.314   928  2998 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-15 14:46:43.320   928  2998 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-15 14:46:43.328   928  2998 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:46:43.333   928  2998 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-15 14:46:43.334   928  2998 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-15 14:46:43.334   928  2998 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-15 14:46:43.334   928  2998 D ConnectivityService:    accepting network in place of null
11-15 14:46:43.334   928  2986 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-15 14:46:43.334   928  2986 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-15 14:46:43.335   928  2998 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-15 14:46:43.358   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 14:46:43.379   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-15 14:46:43.383   928  5812 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110113, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-15 14:46:43.383  3754  3906 W QCNEJ   : |CORE| network available: 101
,11-15 14:46:43.383   928  2998 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-15 14:46:43.383   928  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-15 14:46:43.385  3754  3906 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-15 14:46:43.385   928  2998 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-15 14:46:43.386  3754  3906 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-15 14:46:43.387   928   945 D Tethering: MasterInitialState.processMessage what=3
11-15 14:46:43.387  3754  3906 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-15 14:46:43.401  5033  5046 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-15 14:46:43.401  5033  5046 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-15 14:46:43.401  5033  5046 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-15 14:46:43.401  5033  5046 E SarControlService: no key has been found,reset the power
11-15 14:46:43.402  5033  5071 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-15 14:46:43.402  5033  5071 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-15 14:46:43.402  5033  5071 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-15 14:46:43.402  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 14:46:43.402  5059  5059 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-15 14:46:43.406  4000  4000 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-15 14:46:43.407  5033  5071 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-15 14:46:43.407  5033  5071 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-15 14:46:43.407  5033  5071 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-15 14:46:43.408  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-15 14:46:43.408  5059  5059 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-15 14:46:43.410  4016  4016 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-15 14:46:43.411  5059  5073 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38601c0 HexData = [00000000ec03000000000000ffffffff]
,11-15 14:46:43.411  5059  5073 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 14:46:43.411  5059  5073 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-15 14:46:43.414  5059  5073 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38601c0 HexData = [00000000ed03000000000000ffffffff]
,11-15 14:46:43.414  5059  5073 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-15 14:46:43.414  5059  5073 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-15 14:46:43.415  4016  4016 D SystemUpdateService: onCreate
11-15 14:46:43.416  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 14:46:43.416  5033  5043 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-15 14:46:43.417  5059  5059 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-15 14:46:43.417  5033  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-15 14:46:43.420  4016  4016 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-15 14:46:43.429  4016  4016 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-15 14:46:43.434  4016  5386 I iu.UploadsManager: num queued entries: 0
,11-15 14:46:43.434  4016  5386 I iu.UploadsManager: num updated entries: 0
11-15 14:46:43.434  4016  5386 I iu.SyncManager: NEXT; no task
,11-15 14:46:43.437  4016  5826 I SystemUpdateService: active receiver: enabled
,11-15 14:46:43.441  4016  4016 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-15 14:46:43.442  4016  4016 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-15 14:46:43.444  5774  5774 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-15 14:46:43.447  5774  5774 D SprintDMHelper: simOperator: 
,11-15 14:46:43.447  5774  5774 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-15 14:46:43.453   928  5811 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.211.46,2a00:1450:4016:805::200e
,11-15 14:46:43.466  4016  5826 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-15 14:46:43.481  4016  5826 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-15 14:46:43.481  4016  5826 I SystemUpdateService: now status is 0 (complete)
11-15 14:46:43.481  4016  5826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-15 14:46:43.481  4016  5826 I SystemUpdateService: file has been verified
11-15 14:46:43.481  4016  5826 I SystemUpdateService: OTA package size = 21989297
,11-15 14:46:43.486  4016  5826 I SystemUpdateService: showing system update notification
,11-15 14:46:43.494   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-15 14:46:43.495  4016  4016 D SystemUpdateService: onDestroy
,11-15 14:46:43.522   928  5811 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Nov 2016 13:46:43 GMT], X-Android-Received-Millis=[1479217603521], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479217603483]}
,11-15 14:46:43.522   928  2998 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-15 14:46:43.523   928  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-15 14:46:43.523   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-15 14:46:43.524   928  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-15 14:46:43.569  4471  5831 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-15 14:46:43.620  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-15 14:46:43.620  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:46:43.620  5592  5592 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 14:46:43.640  5697  5697 D BtGatt.ScanManager: awakened up at time 110371
,11-15 14:46:43.643  5697  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:46:43.652  5697  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 14:46:43.652  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:46:43.653  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-15 14:46:44.156  5697  5697 D BtGatt.ScanManager: awakened up at time 110887
,11-15 14:46:44.158  5697  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:46:44.182  5697  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-15 14:46:44.183  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:44.183  5697  5715 D BtGatt.GattService: current time is 110913952031
11-15 14:46:44.184  5697  5715 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 14:46:44.188  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-15 14:46:44.191  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 14:46:44.195  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,11-15 14:46:44.196  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=110764759844}
11-15 14:46:44.196  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=110764759844}
11-15 14:46:44.198  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = FC:8B:06:69:DB:B6, provideBluetoothMacAddressRequestId = nullextra info = 210]
,11-15 14:46:44.198  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-15 14:46:44.198  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=110464759844}
11-15 14:46:44.199  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=110464759844}
,11-15 14:46:44.199  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 61:7E:A4:16:C8:B6, provideBluetoothMacAddressRequestId = nullextra info = 35]
11-15 14:46:44.199  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-15 14:46:44.384   928  2998 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-15 14:46:46.057   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:46:46.116  5592  5639 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-15 14:46:46.117  5592  5639 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-15 14:46:46.117  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-15 14:46:46.117  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-15 14:46:46.118  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-15 14:46:46.118  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.119  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.119  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-15 14:46:46.119  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-15 14:46:46.119  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.119  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.120  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.121  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:46.122  5697  5725 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 14:46:46.123  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-15 14:46:46.124  5697  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:46:46.125  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:46.126  5697  5707 D BtGatt.GattService: stopScan() - queue size =1
11-15 14:46:46.128  5697  5743 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 14:46:46.129  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:46:46.130  5697  5697 D BtGatt.ScanManager: awakened up at time 112861
11-15 14:46:46.130  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.131  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 14:46:46.131  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.131  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-15 14:46:46.132  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.132  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.133  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-15 14:46:46.133  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-15 14:46:46.133  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-15 14:46:46.133  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-15 14:46:46.134  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.134  5592  5639 D BluetoothAdapter: STATE_ON
,11-15 14:46:46.137  5697  5708 D BtGatt.GattService: registerClient() - UUID=548be641-bcf6-448c-a91e-79fa4b4c04f9
11-15 14:46:46.138  5697  5715 D BtGatt.GattService: onClientRegistered() - UUID=548be641-bcf6-448c-a91e-79fa4b4c04f9, clientIf=5
11-15 14:46:46.138  5592  5603 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-15 14:46:46.139  5697  5707 D BtGatt.GattService: start scan with filters
,11-15 14:46:46.144  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-15 14:46:46.144  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.144  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-15 14:46:46.144  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.144  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.144  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:46.145  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 14:46:46.145  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-15 14:46:46.145  5592  5639 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-15 14:46:46.145  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-15 14:46:46.145  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-15 14:46:46.145  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 14:46:46.145  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-15 14:46:46.145  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.145  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-15 14:46:46.145  5697  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
11-15 14:46:46.145  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:46.145  5697  5715 D BtGatt.GattService: current time is 112876091821
11-15 14:46:46.145  5697  5715 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -78, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:46:46.146  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-15 14:46:46.146  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:46:46.146  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-15 14:46:46.146  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-15 14:46:46.146  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-15 14:46:46.146  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-15 14:46:46.146  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-15 14:46:46.147  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 1. Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.147  5592  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-15 14:46:46.147  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=111226511562}
11-15 14:46:46.147  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=111226511562}
11-15 14:46:46.147  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D5:91:A5:EC:E3:B6, provideBluetoothMacAddressRequestId = nullextra info = 116]
11-15 14:46:46.147  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
11-15 14:46:46.147  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-15 14:46:46.148  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-15 14:46:46.148  5592  5838 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-15 14:46:46.148  5592  5639 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-15 14:46:46.152  5708  5708 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[29603]" dev="sockfs" ino=29603 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:46.152  5708  5708 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[29603]" dev="sockfs" ino=29603 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-15 14:46:46.154  5592  5838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-15 14:46:46.155  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.155  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.155  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.155  5697  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-15 14:46:46.155  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-15 14:46:46.155  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:46.155  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-15 14:46:46.155  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-15 14:46:46.155  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-15 14:46:46.155  5697  5718 D BtGatt.ScanManager: stopping BLe Batch
11-15 14:46:46.155  5592  5639 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-15 14:46:46.156  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:46.156  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.156  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-15 14:46:46.156  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-15 14:46:46.156  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.156  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.156  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.159  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:46.161  5697  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-15 14:46:46.161  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:46:46.161  5697  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 14:46:46.163  5697  5743 D BtGatt.GattService: registerClient() - UUID=a42b2fbc-813e-4c47-9b40-4be20b0f5ab1
,11-15 14:46:46.164  5697  5715 D BtGatt.GattService: onClientRegistered() - UUID=a42b2fbc-813e-4c47-9b40-4be20b0f5ab1, clientIf=6
,11-15 14:46:46.164  5592  5603 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-15 14:46:46.165  5697  5717 D BtGatt.AdvertiseManager: message : 0
,11-15 14:46:46.167  5697  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 14:46:46.167  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:46.168  5697  5717 D BtGatt.AdvertiseManager: starting multi advertising
,11-15 14:46:46.169  5697  5718 D BtGatt.ScanManager: handling starting scan
,11-15 14:46:46.178  5697  5715 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-15 14:46:46.182  5697  5715 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-15 14:46:46.182  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:46.182  5697  5718 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-15 14:46:46.186  5697  5715 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-15 14:46:46.187  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.187  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-15 14:46:46.188  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-15 14:46:46.188  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-15 14:46:46.189  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-15 14:46:46.189  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.191  5697  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-15 14:46:46.191  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:46.191  5697  5718 D BtGatt.ScanManager: Starting BLE batch scan
11-15 14:46:46.191  5697  5718 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-15 14:46:46.191  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.191  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.191  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:46.191  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState:, State changed from STARTING to RUNNING
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.192  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-15 14:46:46.192  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.195  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.195  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-15 14:46:46.195  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.195  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.195  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:46.195  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-15 14:46:46.201  5697  5715 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-15 14:46:46.201  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:46:46.205  5697  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-15 14:46:46.205  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:46:46.696  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-15 14:46:46.697  5592  5592 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-15 14:46:46.697  5592  5592 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-15 14:46:46.993   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-15 14:46:46.993   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-15 14:46:49.088   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:46:49.196  5592  5639 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-15 14:46:49.196  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-15 14:46:49.196  5592  5639 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-15 14:46:49.197  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-15 14:46:49.197  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-15 14:46:49.197  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-15 14:46:49.197  5592  5838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-15 14:46:49.197  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-15 14:46:49.197  5592  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-15 14:46:49.198  5592  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-15 14:46:49.198  5592  5838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-15 14:46:49.198  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-15 14:46:49.198  5592  5592 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-15 14:46:49.198  5592  5639 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ff378a removed from the list
11-15 14:46:49.198  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-15 14:46:49.198  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-15 14:46:49.198  5592  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-15 14:46:49.198  5592  5592 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-15 14:46:49.199  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-15 14:46:49.199  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-15 14:46:49.199  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:49.199  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.200  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.200  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-15 14:46:49.200  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.202  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:49.203  5697  5725 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-15 14:46:49.203  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-15 14:46:49.204  5697  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-15 14:46:49.205  5592  5639 D BluetoothAdapter: STATE_ON
11-15 14:46:49.207  5697  5743 D BtGatt.GattService: stopScan() - queue size =1
11-15 14:46:49.209  5697  5707 D BtGatt.GattService: unregisterClient() - clientIf=5
11-15 14:46:49.210  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-15 14:46:49.211  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:49.211  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-15 14:46:49.211  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.211  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:49.211  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.211  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-15 14:46:49.211  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.213  5697  5717 D BtGatt.AdvertiseManager: message : 1
11-15 14:46:49.216  5697  5717 D BtGatt.AdvertiseManager: stop advertise for client 6
11-15 14:46:49.217  5697  5697 D BtGatt.ScanManager: awakened up at time 115947
,11-15 14:46:49.229  5697  5715 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-15 14:46:49.229  5697  5715 D BtGatt.GattService: Client app is not null!
,11-15 14:46:49.230  5697  5743 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-15 14:46:49.231  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-15 14:46:49.231  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:49.231  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-15 14:46:49.231  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.231  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.232  5592  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.232  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-15 14:46:49.232  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-15 14:46:49.232  5592  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-15 14:46:49.233  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:49.234  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.234  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:49.235  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-15 14:46:49.235  5592  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-15 14:46:49.235  5592  5639 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@252e1fb removed from the list
11-15 14:46:49.235  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-15 14:46:49.235  5592  5639 D io.jxcore.node.ConnectivityMonitor: stop
11-15 14:46:49.235  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-15 14:46:49.235  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:49.235  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.235  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:46:49.236  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,11-15 14:46:49.236  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.236  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.236  5592  5592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
,11-15 14:46:49.236  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.237  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-15 14:46:49.237  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-15 14:46:49.237  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-15 14:46:49.237  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-15 14:46:49.237  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-15 14:46:49.237  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-15 14:46:49.237  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.237  5592  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-15 14:46:49.237  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.237  5592  5592 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.238  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.238  5592  5592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-15 14:46:49.238  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.238  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-15 14:46:49.238  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-15 14:46:49.238  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.238  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-15 14:46:49.238  5592  5592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-15 14:46:49.238  5592  5592 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-15 14:46:49.239  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,11-15 14:46:49.240  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-15 14:46:49.241  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-15 14:46:49.242  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-15 14:46:49.246  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-15 14:46:49.247  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-15 14:46:49.248  5592  5639 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
11-15 14:46:49.257  5697  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-15 14:46:49.257  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:49.257  5697  5715 D BtGatt.GattService: current time is 115987898891
11-15 14:46:49.257  5697  5715 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -90, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -99, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-15 14:46:49.257  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-15 14:46:49.258  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-15 14:46:49.258  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-15 14:46:49.258  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-15 14:46:49.258  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-15 14:46:49.258  5697  5715 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-15 14:46:49.264  5697  5715 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-15 14:46:49.264  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:49.264  5697  5718 D BtGatt.ScanManager: stopping BLe Batch
,11-15 14:46:49.270  5697  5715 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-15 14:46:49.270  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-15 14:46:49.270  5697  5718 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-15 14:46:49.275  5697  5715 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-15 14:46:49.275  5697  5715 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-15 14:46:49.739  5592  5592 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-15 14:46:51.252  5592  5639 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-15 14:46:51.336   928  2998 D ConnectivityService: handlePromptUnvalidated 101
,11-15 14:46:51.401  5592  5840 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 151, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 14:46:51.401  5592  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:46:51.994   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:52.225  5592  5840 W !!      : call onHalfStreamCopied
,11-15 14:46:52.225  5592  5840 I testCopyDataAndClose: closing input stream
,11-15 14:46:52.995   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 151, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 151, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-15 14:46:53.009  5592  5840 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-15 14:46:53.494   928  2986 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-15 14:46:53.996   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:54.318   928  2986 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-15 14:46:54.997   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:55.998   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:46:56.998   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-15 14:46:57.358  5592  5639 I StreamCopyingThreadTest: Starting test: testRun
,11-15 14:46:57.364  5592  5841 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: My test thread name). Connection data: Peer properties: [null null].
11-15 14:46:57.364  5592  5841 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:47:02.000   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:02.372  5592  5842 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-15 14:47:02.375  5592  5639 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-15 14:47:02.571  5592  5843 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 14:47:02.571  5592  5843 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:47:03.001   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:04.002   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-15 14:47:04.224  5592  5843 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-15 14:47:05.003   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:06.004   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:07.005   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-15 14:47:07.664  3677  3879 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-15 14:47:07.664  3677  3879 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-15 14:47:07.702  3601  3601 I ConfigService: onCreate
,11-15 14:47:08.867  5592  5639 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-15 14:47:08.870  5592  5845 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-15 14:47:08.870  5592  5845 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:47:08.870  5592  5845 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: My test thread name). Connection data: Peer properties: [null null].
11-15 14:47:08.870  5592  5845 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-15 14:47:08.871  5592  5845 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-15 14:47:08.872  5592  5639 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-15 14:47:08.873  5592  5639 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-15 14:47:08.874  5592  5639 I StreamCopyingThreadTest: Starting test: testRunWithException
11-15 14:47:08.876  5592  5846 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-15 14:47:08.876  5592  5846 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-15 14:47:08.877  5592  5846 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 163, thread name: My test thread name): Test exception.
11-15 14:47:08.877  5592  5846 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-15 14:47:08.877  5592  5846 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-15 14:47:08.877  5592  5846 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-15 14:47:08.877  5592  5846 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-15 14:47:08.877  5592  5846 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-15 14:47:08.879  5592  5639 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-15 14:47:08.879  5592  5639 E com.test.thalitest.ThaliTestRunner: 
11-15 14:47:08.879  5592  5639 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 14:47:08.879  5592  5639 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner: The BT listener was bound
11-15 14:47:08.880  5592,  5639 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 14:47:08.880  5592  5639 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: The BT listener was bound
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:216)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 14:47:08.881  5592  5639 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-15 14:47:08.882  5592  5639 E com.test.,thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.Tha,liTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:47:08.882  5592  5639 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-15 14:47:08.885  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG UnitTest_app: 'Running unit tests'
11-15 14:47:08.885  5592  5639 I jxcore-log: 
11-15 14:47:08.885  5592  5639 I jxcore-log: *Native tests were executed*
11-15 14:47:08.885  5592  5639 I jxcore-log: 
11-15 14:47:08.885  5592  5639 I jxcore-log: Total number of executed tests:  82
11-15 14:47:08.885  5592  5639 I jxcore-log: 
11-15 14:47:08.885  5592  5639 I jxcore-log: Number of passed tests:  79
11-15 14:47:08.885  5592  5639 I jxcore-log: 
11-15 14:47:08.885  5592  5639 I jxcore-log: Number of failed tests:  3
11-15 14:47:08.885  5592  5639 I jxcore-log: 
11-15 14:47:08.885  5592  5639 I jxcore-log: Number of ignored tests:  0
11-15 14:47:08.885  5592  5639 I jxcore-log: 
11-15 14:47:08.886  5592  5639 I jxcore-log: Total duration:  39439
11-15 14:47:08.886  5592  5639 I jxcore-log: 
11-15 14:47:08.886  5592  5639 I jxcore-log: Failed to execute UT.
11-15 14:47:08.886  5592  5639 I jxcore-log: 
11-15 14:47:08.887  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-15 14:47:08.887  5592  5639 I jxcore-log: 
11-15 14:47:08.888  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-15 14:47:08.888  5592  5639 I jxcore-log: 
11-15 14:47:08.891  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'netw,orkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 14:47:08.891  5592  5639 I jxcore-log: 
11-15 14:47:08.891  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 14:47:08.891  5592  5639 I jxcore-log: 
11-15 14:47:08.892  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 14:47:08.892  5592  5639 I jxcore-log: 
11-15 14:47:08.893  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 14:47:08.893  5592  5639 I jxcore-log: 
11-15 14:47:08.894  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 14:47:08.894  5592  5639 I jxcore-log: 
11-15 14:47:08.894  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 14:47:08.894  5592  5639 I jxcore-log: 
11-15 14:47:08.894  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.894  5592  5639 I jxcore-log: 
11-15 14:47:08.894  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 14:47:08.894  5592  5639 I jxcore-log: 
11-15 14:47:08.895  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 14:47:08.895  5592  5639 I jxcore-log: 
11-15 14:47:08.895  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.895  5592  5639 I jxcore-log: 
11-15 14:47:08.895  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 14:47:08.895  5592  5639 I jxcore-log: 
11-15 14:47:08.895  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 14:47:08.895  5592  5639 I jxcore-log: 
11-15 14:47:08.895  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.895  5592  5639 I jxcore-log: 
11-15 14:47:08.896  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 14:47:08.896  5592  5639 I jxcore-log: 
11-15 14:47:08.896  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.896  5592  5639 I jxcore-log: 
11-15 14:47:08.896  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 14:47:08.896  5592  5639 I jxcore-log: 
11-15 14:47:08.897  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 14:47:08.897  5592  5639 I jxcore-log: 
11-15 14:47:08.897  5592,  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 14:47:08.897  5592  5639 I jxcore-log: 
11-15 14:47:08.897  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.897  5592  5639 I jxcore-log: 
11-15 14:47:08.897  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 14:47:08.897  5592  5639 I jxcore-log: 
11-15 14:47:08.897  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 14:47:08.897  5592  5639 I jxcore-log: 
11-15 14:47:08.897  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-15 14:47:08.897  5592  5639 I jxcore-log: 
11-15 14:47:08.898  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 14:47:08.898  5592  5639 I jxcore-log: 
11-15 14:47:08.898  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-15 14:47:08.898  5592  5639 I jxcore-log: 
11-15 14:47:08.898  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 14:47:08.898  5592  5639 I jxcore-log: 
11-15 14:47:08.898  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-15 14:47:08.898  5592  5639 I jxcore-log: 
11-15 14:47:08.899  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-15 14:47:08.899  5592  5639 I jxcore-log: 
11-15 14:47:08.899  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-15 14:47:08.899  5592  5639 I jxcore-log: 
11-15 14:47:08.900  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 14:47:08.900  5592  5639 I jxcore-log: 
11-15 14:47:08.900  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.900  5592  5639 I jxcore-log: 
11-15 14:47:08.901  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-15 14:47:08.901  5592  5639 I jxcore-log: 
11-15 14:47:08.901  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 14:47:08.901  5592  5639 I jxcore-log: 
11-15 14:47:08.901  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.901  5592  5639 I jxcore-log: 
11-15 14:47:08.901  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-15 14:47:08.901  5592  5639 I jxcore-log: 
11-15 14:47:08.901  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-15 14:47:08.901  5592  5639 I jxcore-log: 
11-15 14:47:08.902  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.902  5592  5639 I jxcore-log: 
11-15 14:47:08.902  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-15 14:47:08.902  5592  5639 I jxcore-log: 
11-15 14:47:08.902  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-15 14:47:08.902  5592  5639 I jxcore-log: 
11-15 14:47:08.907  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-15 14:47:08.907  5592  5639 I jxcore-log: 
11-15 14:47:08.907  5592  5639 I jxcore-log: 2016-11-15 13:47:08 - WARN testUtils: 'myNameCallback not set!'
11-15 14:47:08.907  5592  5639 I jxcore-log: 
11-15 14:47:08.908  5592  5592 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-15 14:47:10.247   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:47:10.917  5592  5639 I jxcore-log: 2016-11-15 13:47:10 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-15 14:47:10.917  5592  5639 I jxcore-log: 
,11-15 14:47:10.919  5592  5639 I jxcore-log: 2016-11-15 13:47:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-15 14:47:10.919  5592  5639 I jxcore-log: 
,11-15 14:47:11.249  5592  5639 I jxcore-log: 2016-11-15 13:47:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-15 14:47:11.249  5592  5639 I jxcore-log: 
,11-15 14:47:11.263  5592  5639 I jxcore-log: 2016-11-15 13:47:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-15 14:47:11.263  5592  5639 I jxcore-log: 
,11-15 14:47:12.358  5592  5639 I jxcore-log: 2016-11-15 13:47:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-15 14:47:12.358  5592  5639 I jxcore-log: 
,11-15 14:47:12.522  5592  5639 I jxcore-log: 2016-11-15 13:47:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-15 14:47:12.522  5592  5639 I jxcore-log: 
,11-15 14:47:12.528  5592  5639 I jxcore-log: 2016-11-15 13:47:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-15 14:47:12.528  5592  5639 I jxcore-log: 
,11-15 14:47:12.540  5592  5639 I jxcore-log: 2016-11-15 13:47:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-15 14:47:12.540  5592  5639 I jxcore-log: 
,11-15 14:47:12.737  3601  3601 I ConfigService: onDestroy
,11-15 14:47:13.024  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-15 14:47:13.024  5592  5639 I jxcore-log: 
,11-15 14:47:13.068  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-15 14:47:13.068  5592  5639 I jxcore-log: 
,11-15 14:47:13.081  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-15 14:47:13.081  5592  5639 I jxcore-log: 
,11-15 14:47:13.086  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-15 14:47:13.086  5592  5639 I jxcore-log: 
,11-15 14:47:13.279   928  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-15 14:47:13.355  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-15 14:47:13.355  5592  5639 I jxcore-log: 
,11-15 14:47:13.476  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-15 14:47:13.476  5592  5639 I jxcore-log: 
,11-15 14:47:13.853  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-15 14:47:13.853  5592  5639 I jxcore-log: 
,11-15 14:47:13.860  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-15 14:47:13.860  5592  5639 I jxcore-log: 
,11-15 14:47:13.864  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-15 14:47:13.864  5592  5639 I jxcore-log: 
,11-15 14:47:13.867  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-15 14:47:13.867  5592  5639 I jxcore-log: 
,11-15 14:47:13.873  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-15 14:47:13.873  5592  5639 I jxcore-log: 
,11-15 14:47:13.910  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-15 14:47:13.910  5592  5639 I jxcore-log: 
,11-15 14:47:13.916  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-15 14:47:13.916  5592  5639 I jxcore-log: 
,11-15 14:47:13.945  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-15 14:47:13.945  5592  5639 I jxcore-log: 
,11-15 14:47:13.983  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-15 14:47:13.983  5592  5639 I jxcore-log: 
,11-15 14:47:13.990  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-15 14:47:13.990  5592  5639 I jxcore-log: 
,11-15 14:47:13.997  5592  5639 I jxcore-log: 2016-11-15 13:47:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-15 14:47:13.997  5592  5639 I jxcore-log: 
,11-15 14:47:14.012  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-15 14:47:14.012  5592  5639 I jxcore-log: 
,11-15 14:47:14.026  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-15 14:47:14.026  5592  5639 I jxcore-log: 
,11-15 14:47:14.033  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-15 14:47:14.033  5592  5639 I jxcore-log: 
,11-15 14:47:14.039  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-15 14:47:14.039  5592  5639 I jxcore-log: 
,11-15 14:47:14.052  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-15 14:47:14.052  5592  5639 I jxcore-log: 
,11-15 14:47:14.070  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-15 14:47:14.070  5592  5639 I jxcore-log: 
,11-15 14:47:14.084  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-15 14:47:14.084  5592  5639 I jxcore-log: 
,11-15 14:47:14.096  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-15 14:47:14.096  5592  5639 I jxcore-log: 
,11-15 14:47:14.109  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-15 14:47:14.109  5592  5639 I jxcore-log: 
,11-15 14:47:14.119  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-15 14:47:14.119  5592  5639 I jxcore-log: 
,11-15 14:47:14.132  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-15 14:47:14.132  5592  5639 I jxcore-log: 
,11-15 14:47:14.142  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-15 14:47:14.142  5592  5639 I jxcore-log: 
,11-15 14:47:14.149  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-15 14:47:14.149  5592  5639 I jxcore-log: 
,11-15 14:47:14.170  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-15 14:47:14.170  5592  5639 I jxcore-log: 
,11-15 14:47:14.176  5592  5639 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-15 14:47:14.177  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - INFO testUtils: 'BLE multiple advertisement supported'
11-15 14:47:14.177  5592  5639 I jxcore-log: 
,11-15 14:47:14.301  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:14.301  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:14.301  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:14.301  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:14.301  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:14.301  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:14.301  5592  5639 I jxcore-log: 
,11-15 14:47:14.541  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:14.541  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:14.541  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:14.541  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:14.541  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:14.541  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:14.541  5592  5639 I jxcore-log: 
,11-15 14:47:14.544  5592  5639 I jxcore-log: 2016-11-15 13:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:14.544  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:14.544  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:14.544  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:14.544  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:14.544  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:14.544  5592  5639 I jxcore-log: 
,11-15 14:47:15.177  5592  5639 I jxcore-log: 2016-11-15 13:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:15.177  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:15.177  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:15.177  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:15.177  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:15.177  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:15.177  5592  5639 I jxcore-log: 
,11-15 14:47:15.181  5592  5639 I jxcore-log: 2016-11-15 13:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:15.181  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:15.181  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:15.181  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:15.181  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:15.181  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:15.181  5592  5639 I jxcore-log: 
,11-15 14:47:15.765  5592  5639 I jxcore-log: 2016-11-15 13:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:15.765  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:15.765  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:15.765  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:15.765  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:15.765  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:15.765  5592  5639 I jxcore-log: 
,11-15 14:47:15.771  5592  5639 I jxcore-log: 2016-11-15 13:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:15.771  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:15.771  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:15.771  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:15.771  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:15.771  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:15.771  5592  5639 I jxcore-log: 
,11-15 14:47:16.806  5592  5639 I jxcore-log: 2016-11-15 13:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:16.806  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:16.806  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:16.806  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:16.806  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:16.806  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:16.806  5592  5639 I jxcore-log: 
,11-15 14:47:16.814  5592  5639 I jxcore-log: 2016-11-15 13:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:16.814  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:16.814  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:16.814  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:16.814  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:16.814  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:16.814  5592  5639 I jxcore-log: 
,11-15 14:47:17.006   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:17.847  5592  5639 I jxcore-log: 2016-11-15 13:47:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:17.847  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:17.847  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:17.847  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:17.847  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:17.847  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:17.847  5592  5639 I jxcore-log: 
,11-15 14:47:17.850  5592  5639 I jxcore-log: 2016-11-15 13:47:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:17.850  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:17.850  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:17.850  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:17.850  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:17.850  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:17.850  5592  5639 I jxcore-log: 
,11-15 14:47:18.007   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:19.008   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:19.314  5592  5639 I jxcore-log: 2016-11-15 13:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:19.314  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:19.314  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:19.314  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:19.314  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:19.314  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:19.314  5592  5639 I jxcore-log: 
,11-15 14:47:19.320  5592  5639 I jxcore-log: 2016-11-15 13:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:19.320  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:19.320  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:19.320  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:19.320  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:19.320  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:19.320  5592  5639 I jxcore-log: 
,11-15 14:47:20.010   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:20.352  5592  5639 I jxcore-log: 2016-11-15 13:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:20.352  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:20.352  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:20.352  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:20.352  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:20.352  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:20.352  5592  5639 I jxcore-log: 
,11-15 14:47:20.357  5592  5639 I jxcore-log: 2016-11-15 13:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:20.357  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:20.357  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:20.357  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:20.357  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:20.357  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:20.357  5592  5639 I jxcore-log: 
,11-15 14:47:21.011   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-15 14:47:21.386  5592  5639 I jxcore-log: 2016-11-15 13:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:21.386  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:21.386  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:21.386  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:21.386  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:21.386  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:21.386  5592  5639 I jxcore-log: 
,11-15 14:47:21.390  5592  5639 I jxcore-log: 2016-11-15 13:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:21.390  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:21.390  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:21.390  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:21.390  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:21.390  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:21.390  5592  5639 I jxcore-log: 
,11-15 14:47:22.012   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-15 14:47:22.423  5592  5639 I jxcore-log: 2016-11-15 13:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:22.423  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:22.423  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:22.423  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:22.423  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:22.423  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:22.423  5592  5639 I jxcore-log: 
,11-15 14:47:22.427  5592  5639 I jxcore-log: 2016-11-15 13:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:22.427  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:22.427  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:22.427  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:22.427  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:22.427  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:22.427  5592  5639 I jxcore-log: 
,11-15 14:47:23.310   928  2986 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-15 14:47:23.488  5592  5639 I jxcore-log: 2016-11-15 13:47:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:23.488  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:23.488  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:23.488  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:23.488  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:23.488  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:23.488  5592  5639 I jxcore-log: 
,11-15 14:47:23.492  5592  5639 I jxcore-log: 2016-11-15 13:47:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:23.492  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:23.492  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:23.492  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:23.492  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:23.492  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:23.492  5592  5639 I jxcore-log: 
,11-15 14:47:24.533  5592  5639 I jxcore-log: 2016-11-15 13:47:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:24.533  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:24.533  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:24.533  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:24.533  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:24.533  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:24.533  5592  5639 I jxcore-log: 
,11-15 14:47:24.538  5592  5639 I jxcore-log: 2016-11-15 13:47:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:24.538  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:24.538  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:24.538  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:24.538  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:24.538  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:24.538  5592  5639 I jxcore-log: 
,11-15 14:47:25.571  5592  5639 I jxcore-log: 2016-11-15 13:47:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:25.571  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:25.571  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:25.571  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:25.571  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:25.571  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:25.571  5592  5639 I jxcore-log: 
,11-15 14:47:25.578  5592  5639 I jxcore-log: 2016-11-15 13:47:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:25.578  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:25.578  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:25.578  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:25.578  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:25.578  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:25.578  5592  5639 I jxcore-log: 
,11-15 14:47:25.820   928  5812 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152550, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-15 14:47:27.300  5592  5639 I jxcore-log: 2016-11-15 13:47:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:27.300  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:27.300  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:27.300  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:27.300  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:27.300  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:27.300  5592  5639 I jxcore-log: 
,11-15 14:47:27.305  5592  5639 I jxcore-log: 2016-11-15 13:47:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:27.305  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:27.305  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:27.305  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:27.305  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:27.305  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:27.305  5592  5639 I jxcore-log: 
,11-15 14:47:28.330  5592  5639 I jxcore-log: 2016-11-15 13:47:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:28.330  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:28.330  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:28.330  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:28.330  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:28.330  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:28.330  5592  5639 I jxcore-log: 
,11-15 14:47:28.334  5592  5639 I jxcore-log: 2016-11-15 13:47:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:28.334  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:28.334  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:28.334  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:28.334  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:28.334  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:28.334  5592  5639 I jxcore-log: 
,11-15 14:47:29.365  5592  5639 I jxcore-log: 2016-11-15 13:47:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-15 14:47:29.365  5592  5639 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-15 14:47:29.365  5592  5639 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-15 14:47:29.365  5592  5639 I jxcore-log: emit@events.js:82:1
11-15 14:47:29.365  5592  5639 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-15 14:47:29.365  5592  5639 I jxcore-log: emit@events.js:82:1'
11-15 14:47:29.365  5592  5639 I jxcore-log: 
,11-15 14:47:29.374  5592  5639 E jxcore  : Error!: error is undefined
11-15 14:47:29.374  5592  5639 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-15 14:47:29.378  5592  5639 I jxcore-log: 2016-11-15 13:47:29 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-15 14:47:29.378  5592  5639 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-15 14:47:29.378  5592  5639 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-15 14:47:29.378  5592  5639 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-15 14:47:29.378  5592  5639 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-15 14:47:29.378  5592  5639 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-15 14:47:29.378  5592  5639 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-15 14:47:29.378  5592  5639 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-15 14:47:29.379  5592  5639 I jxcore-log: 2016-11-15 13:47:29 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-15 14:47:29.379  5592  5639 I jxcore-log: 
,11-15 14:47:29.381  5592  5639 E jxcore-log: TypeError: 
11-15 14:47:29.381  5592  5639 E jxcore-log: error is undefined
11-15 14:47:29.381  5592  5639 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-15 14:47:29.381  5592  5639 E jxcore-log: 
,11-15 14:47:29.479   928  3761 D GraphicsStats: Buffer count: 2
11-15 14:47:29.479   928  3436 I WindowState: WIN DEATH: Window{7bb52a6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-15 14:47:29.480   928  2996 D WifiService: Client connection lost with reason: 4
,11-15 14:47:29.490  3863  4443 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-15 14:47:29.497   527   527 I Zygote  : Process 5592 exited cleanly (139)
,11-15 14:47:29.501   928  3437 I ActivityManager: Process com.test.thalitest (pid 5592) has died
11-15 14:47:29.501   928  3437 W ActivityManager: Force removing ActivityRecord{6e2ca6e u0 com.test.thalitest/.MainActivity t68}: app died, no saved state
,11-15 14:47:29.553   928   938 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5592 uid 10077
,11-15 14:47:29.554  3677  3677 I Keyboard.Facilitator: onFinishInput()
,11-15 14:47:29.552   938   938 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[28927]" dev="sockfs" ino=28927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-15 14:47:29.552   938   938 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[28927]" dev="sockfs" ino=28927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-15 14:47:29.609  4000  5852 I MicroRecognitionRnrImpl: Starting detection.
,11-15 14:47:29.609  4000  5853 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@29ab960
,11-15 14:47:29.611   512  5855 I AudioFlinger: AudioFlinger's thread 0xf1c00000 ready to run
,11-15 14:47:29.615   512  3047 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-15 14:47:29.617  4000  5853 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@29ab960
,11-15 14:47:29.626   512  5855 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-15 14:47:29.626   512  5855 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-15 14:47:29.627   512  5855 I ACDB-LOADER: ACDB AFE returned = -19
11-15 14:47:29.627   512  5855 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-15 14:47:29.627   512  5855 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-15 14:47:29.627   512  5855 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-15 14:47:29.633   512  5855 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-15 14:47:29.706  4000  4000 I HotwordWorkerImpl: onReady
,11-15 14:47:29.804  5847  5847 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-15 14:47:29.808  5847  5847 D AndroidRuntime: CheckJNI is OFF
,11-15 14:47:29.832  5847  5847 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-15 14:47:29.857  5847  5847 I Radio-JNI: register_android_hardware_Radio DONE
,11-15 14:47:29.872  5847  5847 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-15 14:47:29.879   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-15 14:47:29.983   928   952 I art     : Starting a blocking GC Explicit
,11-15 14:47:30.088  3843  4052 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-15 14:47:30.106   928   952 I art     : Explicit concurrent mark sweep GC freed 77362(4MB) AllocSpace objects, 20(596KB) LOS objects, 33% free, 28MB/43MB, paused 2.782ms total 122.382ms
,11-15 14:47:30.127   928   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-15 14:47:30.131  5847  5847 I art     : System.exit called, status: 0
,11-15 14:47:30.131  5847  5847 I AndroidRuntime: VM exiting with result code 0.
,11-15 14:47:30.136   928   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-15 14:47:30.148  3677  3677 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-15 14:47:30.150  5697  5697 D BluetoothMapAppObserver: onReceive
11-15 14:47:30.150  5697  5697 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-15 14:47:30.151  3863  4137 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-15 14:47:30.156   928  2962 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-15 14:47:30.170  3677  5866 I Keyboard.Facilitator.DecoderInitializer: run()
,11-15 14:47:30.174  3421  5867 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-15 14:47:30.191  3677  5866 I Decoder : createOrResetDecoder
,11-15 14:47:30.205  3794  3794 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-15 14:47:30.213  3601  3601 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-15 14:47:30.213  3601  3601 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-15 14:47:30.229   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-15 14:47:30.232  4016  5872 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-15 14:47:30.232  4016  5872 D AccountUtils: Clearing selected account for com.test.thalitest
,11-15 14:47:30.244  4016  5872 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-15 14:47:30.249  3601  3601 I ConfigService: onCreate
,11-15 14:47:30.260  4016  4016 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-15 14:47:30.260  4016  4016 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-15 14:47:30.268    27    27 W kworker/2:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 14:47:30.273  4016  4016 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-15 14:47:30.273  4016  4016 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-15 14:47:30.276  4016  5878 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-15 14:47:30.276  4016  5878 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-15 14:47:30.278  4016  5878 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
11-15 14:47:30.278    27    27 W kworker/2:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-15 14:47:30.292    27    27 W kworker/2:1: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-15 14:47:30.279  4016  5878 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,11-15 14:47:30.283  4000  5881 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-15 14:47:30.284  4016  5878 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
,11-15 14:47:30.284  4016  5878 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
11-15 14:47:30.284  4016  5878 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
11-15 14:47:30.290  4016  5878 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-15 14:47:30.290  4016  5878 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-15 14:47:30.295  4016  5878 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,11-15 14:47:30.295  4016  5878 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 0
11-15 14:47:30.295  4016  5878 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 0
11-15 14:47:30.295  4016  5878 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
11-15 14:47:30.303  3677  5866 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-15 14:47:30.312  4000  5881 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-15 14:47:30.315  3843  4429 E ObservedEventLogger: Failed to write the stream file
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2439: open failed: EROFS (Read-only file system)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	... 16 more
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: Failed to write the stream file
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2440: open failed: EROFS (Read-only file system)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.a,pps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:47:30.315  3843  4429 E ObservedEventLogger: 	... 16 more
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: Failed to write the stream file
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2441: open failed: EROFS (Read-only file system)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:47:30.316  3843  4429 E ObservedEventLogger: 	... 16 more
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: Failed to write the stream file
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2442: open failed: EROFS (Read-only file system)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:47:30.317  3843  4429 E ObservedEventLogger: 	... 16 more
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: Failed to write the stream file
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2443: open failed: EROFS (Read-only file system)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:47:30.318  3843  4429 E ObservedEventLogger: 	... 16 more
11-15 14:47:30.320   928  3761 I ActivityManager: Start proc 5885:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
11-15 14:47:30.325  3421  5867 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
11-15 14:47:30.327  3421  5867 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-15 14:47:30.327  3421  5867 E AndroidRuntime: Process: android.process.acore, PID: 3421
11-15 14:47:30.327  3421  5867 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:47:30.327  3421  5867 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 14:47:30.335   928   939 I ActivityManager: Start proc 5896:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-15 14:47:30.337  4000  5881 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
11-15 14:47:30.338  4000  5881 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
11-15 14:47:30.338  4000  5881 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4000
11-15 14:47:30.338  4000  5881 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-15 14:47:30.338  4000  5881 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: Can't write: system_app_crash
11-15 14:47:30.343   928  5903 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:47:30.343   928  5903 E DropBoxManagerService: 	... 5 more
11-15 14:47:30.348   407   407 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[33914]" dev="sockfs" ino=33914 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-15 14:47:30.348   407   407 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[33914]" dev="sockfs" ino=33914 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 14:47:30.353   928  5910 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-15 14:47:30.357   928  5912 E DropBoxManagerService: Can't write: system_app_crash
11-15 14:47:30.357   928  5912 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-15 14:47:30.357   928  5912 E DropBoxManagerService: 	... 5 more
11-15 14:47:30.352   410   410 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[33916]" dev="sockfs" ino=33916 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 14:47:30.352   410   410 W Binder_2: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[33916]" dev="sockfs" ino=33916 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-15 14:47:30.379  4016  5880 W BaseAppContext: Using Auth Proxy for data requests.
11-15 14:47:30.382  5885  5885 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm64
11-15 14:47:30.382  4016  5880 W BaseAppContext: Using Auth Proxy for data requests.
11-15 14:47:30.385  5885  5885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,11-15 14:47:30.395  4016  5915 I GMPM-SVC: App measurement is starting up
,11-15 14:47:30.398  4016  5915 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-15 14:47:30.399  4016  5915 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-15 14:47:30.408   928   928 I ActivityManager: Start proc 5917:com.android.documentsui/u0a42 for broadcast com.android.documentsui/.PackageReceiver
,11-15 14:47:30.415  4016  4016 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-15 14:47:30.444   928   938 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/4016 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-15 14:47:30.491  4016  5877 W DriveInitializer: Awaiting to be initialized
,11-15 14:47:30.491  4016  5932 W DriveInitializer: Background init thread started
,11-15 14:47:30.697   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
