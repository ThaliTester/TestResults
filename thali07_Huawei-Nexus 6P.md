#### Test 899757342c9a24d_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-25 12:41:39.097  3568  4116 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-25 12:41:39.184  3568  4116 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-25 12:41:39.544  5497  5497 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 12:41:39.550  5497  5497 D AndroidRuntime: CheckJNI is OFF
11-25 12:41:39.575  5497  5497 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 12:41:39.607  5497  5497 I Radio-JNI: register_android_hardware_Radio DONE
11-25 12:41:39.622  5497  5497 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-25 12:41:39.628   929   939 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 12:41:39.653  5497  5497 D AndroidRuntime: Shutting down VM
11-25 12:41:39.658  3836  3855 W SearchService: Abort, client detached.
11-25 12:41:39.669  3836  3836 I HotwordDetector: Closing mic
11-25 12:41:39.670  3836  4095 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e4bdb12
11-25 12:41:39.670  3836  4110 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-25 12:41:39.683   929  3292 I ActivityManager: Start proc 5506:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 12:41:39.734   512  4114 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-25 12:41:39.735   512  4114 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-25 12:41:39.738   512  4114 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-25 12:41:39.738   512  4114 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-25 12:41:39.739   512  2874 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-25 12:41:39.742  3836  4101 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-25 12:41:39.742  3836  4109 I MicroRecognitionRnrImpl: Detection finished
11-25 12:41:39.777  5506  5506 I CordovaLog: Changing log level to DEBUG(3)
11-25 12:41:39.778  5506  5506 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 12:41:39.778  5506  5506 D CordovaActivity: CordovaActivity.onCreate()
11-25 12:41:39.781  5506  5506 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-25 12:41:39.800  5506  5506 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-25 12:41:39.862  5506  5506 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 9012-9066)
11-25 12:41:39.862  5506  5506 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 12:41:39.900  5506  5506 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f94b04f}
11-25 12:41:39.901  5506  5506 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-25 12:41:39.901  5506  5506 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-25 12:41:39.907  5506  5506 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-25 12:41:39.909  5506  5506 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 12:41:39.953  5506  5506 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 12:41:39.967  5506  5506 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-25 12:41:39.967  5506  5506 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 12:41:39.967  5506  5506 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 12:41:39.967  5506  5506 I Adreno  : Build Date                       : 12/06/15
11-25 12:41:39.967  5506  5506 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 12:41:39.967  5506  5506 I Adreno  : Local Branch                     : mybranch17112971
11-25 12:41:39.967  5506  5506 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 12:41:39.967  5506  5506 I Adreno  : Remote Branch                    : NONE
11-25 12:41:39.967  5506  5506 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 12:41:40.020   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77b501c:true
,11-25 12:41:40.058   402   402 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[27268]" dev="sockfs" ino=27268 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
11-25 12:41:40.058   402   402 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27268]" dev="sockfs" ino=27268 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 12:41:40.074  5506  5506 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 12:41:40.084  5506  5506 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 12:41:40.088  5506  5506 D PluginManager: init()
,11-25 12:41:40.091  5506  5506 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 12:41:40.110  5506  5506 D CordovaActivity: Started the activity.
11-25 12:41:40.110  5506  5506 D CordovaActivity: Resumed the activity.
,11-25 12:41:40.111   402   402 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33032]" dev="sockfs" ino=33032 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 12:41:40.111   402   402 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33032]" dev="sockfs" ino=33032 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 12:41:40.114  5506  5543 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-25 12:41:40.121  5506  5530 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 12:41:40.118  3293  3293 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[13998]" dev="sockfs" ino=13998 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 12:41:40.118  3293  3293 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13998]" dev="sockfs" ino=13998 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 12:41:40.144  5506  5543 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 12:41:40.244  3292  3292 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31145]" dev="sockfs" ino=31145 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 12:41:40.244  3292  3292 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31145]" dev="sockfs" ino=31145 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 12:41:40.247   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +582ms
,11-25 12:41:40.244  3293  3293 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31144]" dev="sockfs" ino=31144 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 12:41:40.244  3293  3293 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31144]" dev="sockfs" ino=31144 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 12:41:40.250  3541  3541 I Keyboard.Facilitator: onFinishInput()
,11-25 12:41:40.265  5506  5506 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 12:41:40.284  5506  5506 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5506
,11-25 12:41:40.388  5506  5506 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 12:41:40.642  5506  5546 D jxcore_app_log: JniHelper::setJavaVM(0xf4f3c000), pthread_self() = -585889488
,11-25 12:41:40.646  5506  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 12:41:40.646  5506  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 12:41:40.646  5506  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 12:41:40.646  5506  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 12:41:40.646  5506  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-25 12:41:40.646  5506  5546 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98c1ba3 added. We now have 1 listener(s)
,11-25 12:41:40.649  5506  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-25 12:41:40.649  5506  5546 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:41:40.650  5506  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 12:41:40.650  5506  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-25 12:41:40.652  5506  5546 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f6661e added. We now have 1 listener(s)
11-25 12:41:40.652  5506  5546 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:41:40.657   929  2837 D WifiService: New client listening to asynchronous messages
,11-25 12:41:40.657  5506  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 12:41:40.657  5506  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 12:41:40.657  5506  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-25 12:41:40.657  5506  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-25 12:41:40.658  5506  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 12:41:40.658  5506  5546 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-25 12:41:40.658  5506  5546 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-25 12:41:40.659  5506  5546 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 12:41:40.762  5506  5506 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 12:41:40.764  5506  5506 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-25 12:41:40.764  5506  5506 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 12:41:41.282  5506  5553 W jxcore-log: Initializing JXcore engine
11-25 12:41:41.282  5506  5553 W jxcore-log: JXcore engine is ready
,11-25 12:41:41.304  5553  5553 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12345 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-25 12:41:41.304  5553  5553 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13378]" dev="sockfs" ino=13378 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-25 12:41:41.304  5553  5553 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-25 12:41:41.304  5553  5553 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33011]" dev="sockfs" ino=33011 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-25 12:41:41.315  5506  5553 W jxcore-log: Starting JXcore engine
,11-25 12:41:41.365  5506  5553 W jxcore-log: Platform android
11-25 12:41:41.365  5506  5553 W jxcore-log: 
11-25 12:41:41.365  5506  5553 W jxcore-log: Process ARCH arm
11-25 12:41:41.365  5506  5553 W jxcore-log: 
,11-25 12:41:41.516   929  2827 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 12:41:41.553  5506  5553 I jxcore-log: JXcore Cordova bridge is ready!
11-25 12:41:41.553  5506  5553 I jxcore-log: 
,11-25 12:41:41.554  5506  5553 W jxcore-log: JXcore engine is started
,11-25 12:41:41.565  5506  5546 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-25 12:41:41.572  5506  5506 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
11-25 12:41:41.573  5506  5506 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 12:41:43.221  3453  3453 I ConfigService: onDestroy
,11-25 12:41:44.267   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:41:44.676   929   940 I ActivityManager: Killing 5287:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-25 12:41:44.725   929   940 I ActivityManager: Killing 4946:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,11-25 12:41:45.268   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:41:46.269   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:41:47.270   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:41:48.271   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:41:49.272   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 12:41:51.277  5506  5553 I jxcore-log: 2016-11-25 11:41:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 12:41:51.277  5506  5553 I jxcore-log: 
,11-25 12:41:51.279  5506  5553 I jxcore-log: 2016-11-25 11:41:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 12:41:51.279  5506  5553 I jxcore-log: 
,11-25 12:41:51.285  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 12:41:51.285  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 12:41:51.286  5506  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 12:41:51.289  5506  5553 I jxcore-log: 2016-11-25 11:41:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 12:41:51.289  5506  5553 I jxcore-log: 
,11-25 12:41:51.290  5506  5553 I jxcore-log: 2016-11-25 11:41:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 12:41:51.290  5506  5553 I jxcore-log: 
,11-25 12:41:51.542  5506  5553 I jxcore-log: 2016-11-25 11:41:51 - DEBUG UnitTest_app: 'Running unit tests'
11-25 12:41:51.542  5506  5553 I jxcore-log: 
,11-25 12:41:51.542  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 12:41:51.542  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a6775a added. We now have 2 listener(s)
,11-25 12:41:51.543  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 12:41:51.543  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 12:41:51.543  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 12:41:51.543  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:41:51.543  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6da6d8b added. We now have 2 listener(s)
,11-25 12:41:51.544  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:41:51.544  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 12:41:51.545  5506  5553 D executeNativeTests: Running unit tests
,11-25 12:41:51.587  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 12:41:51.587  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 added. We now have 3 listener(s)
,11-25 12:41:51.588  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 12:41:51.588  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 12:41:51.588  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 12:41:51.588  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:41:51.588  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 added. We now have 3 listener(s)
11-25 12:41:51.588  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:41:51.589  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 12:41:51.591  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 12:41:51.591  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 12:41:51.591  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 12:41:51.591  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 12:41:51.592  5506  5553 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-25 12:41:51.592  5506  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 12:41:51.592  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 12:41:51.593  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 12:41:51.593  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 12:41:51.593  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 12:41:51.593  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:41:51.593  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:41:51.593  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:41:51.593  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:41:51.594  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:41:51.594  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-25 12:41:51.594  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 removed from the list
11-25 12:41:51.594  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:41:51.594  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 removed from the list
11-25 12:41:51.594  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:41:51.594  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.594  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.595  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.595  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.595  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.595  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 12:41:51.595  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:41:51.595  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:41:51.595  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:41:51.596  5506  5553 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-25 12:41:51.597  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:41:51.597  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:41:51.597  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:41:51.597  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:41:51.597  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:41:51.597  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:41:51.597  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:41:51.597  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:41:51.597  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:41:51.597  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.597  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.598  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.598  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.598  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.598  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:41:51.598  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:41:51.598  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:41:51.598  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 12:41:51.601  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 12:41:51.602  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:41:51.602  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:41:51.602  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:41:51.602  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:41:51.602  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:41:51.602  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:41:51.602  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:41:51.602  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:41:51.602  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:41:51.602  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.603  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.603  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.603  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.603  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.603  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:41:51.603  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:41:51.603  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:41:51.604  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:41:51.604  5506  5553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 12:41:51.605  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:41:51.606  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 12:41:51.610  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 12:41:51.613  5506  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 12:41:51.614  5506  5553 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 12:41:51.614  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:41:51.614  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 12:41:51.614  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 12:41:51.614  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:41:51.614  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 12:41:51.617  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:41:51.618  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 12:41:51.618  5506  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 12:41:51.618  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 12:41:51.620  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.620  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 12:41:51.620  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:41:51.621  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 12:41:51.621  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 12:41:51.621  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 12:41:51.622  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-25 12:41:51.623  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 12:41:51.624  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.624  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 12:41:51.624  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 12:41:51.624  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 12:41:51.624  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 12:41:51.624  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.624  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:41:51.626  4508  4752 D BtGatt.GattService: registerClient() - UUID=cbffe364-c5f1-4b67-841f-e65cf22efb61
11-25 12:41:51.627  4508  4596 D BtGatt.GattService: onClientRegistered() - UUID=cbffe364-c5f1-4b67-841f-e65cf22efb61, clientIf=5
11-25 12:41:51.628  5506  5516 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 12:41:51.629  4508  4520 D BtGatt.GattService: start scan with filters
11-25 12:41:51.633  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 12:41:51.634  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.634  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 12:41:51.634  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.634  4508  4599 D BtGatt.ScanManager: handling starting scan
11-25 12:41:51.634  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 12:41:51.634  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 12:41:51.634  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.634  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 12:41:51.634  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 12:41:51.634  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.635  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 12:41:51.635  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.635  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.635  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.635  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.637  4508  4599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:41:51.638  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.638  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:41:51.638  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.639  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:51.639  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.639  5506  5553 I io.jxcore.node.ConnectionHelper: start: OK
11-25 12:41:51.641  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.641  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.641  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:41:51.641  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:41:51.644  4508  4596 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 12:41:51.644  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:41:51.646  4508  4599 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 12:41:51.651  4508  4596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 12:41:51.651  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:41:51.651  4508  4599 D BtGatt.ScanManager: Starting BLE batch scan
11-25 12:41:51.651  4508  4599 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 12:41:51.660  4508  4596 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 12:41:51.660  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:41:51.665  4508  4596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 12:41:51.665  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:41:52.143  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 12:41:52.143  5506  5506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:41:52.143  5506  5506 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 12:41:52.625   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 12:41:55.655   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 12:41:56.643  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:41:56.644  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 12:41:56.644  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 12:41:56.644  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:41:56.644  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 12:41:56.644  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:41:56.644  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 12:41:56.644  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 12:41:56.644  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.645  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 12:41:56.645  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 12:41:56.646  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.646  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.646  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.646  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-25 12:41:56.646  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.647  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:41:56.648  4508  4520 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 12:41:56.648  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 12:41:56.649  4508  4599 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 12:41:56.650  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:41:56.652  4508  4751 D BtGatt.GattService: stopScan() - queue size =1
,11-25 12:41:56.654  4508  4752 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 12:41:56.655  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 12:41:56.656  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.656  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 12:41:56.656  4508  4508 D BtGatt.ScanManager: awakened up at time 95860
,11-25 12:41:56.656  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.656  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.656  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.657  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.658  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 12:41:56.658  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-25 12:41:56.659  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.659  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.659  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-25 12:41:56.660  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-25 12:41:56.662  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 12:41:56.663  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:41:56.665  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:41:56.665  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:41:56.665  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.666  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:41:56.666  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 12:41:56.666  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:41:56.666  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:41:56.666  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:41:56.666  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 12:41:56.666  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:41:56.666  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:41:56.666  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 12:41:56.666  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:41:56.666  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 12:41:56.667  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:41:56.667  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:41:56.667  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 12:41:56.667  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 12:41:56.667  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-25 12:41:56.667  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:41:56.667  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 12:41:56.667  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:41:56.667  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 12:41:56.667  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 12:41:56.668  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 12:41:56.699  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 12:41:56.699  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:41:56.699  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 12:41:56.720  4508  4596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-25 12:41:56.720  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:41:56.720  4508  4596 D BtGatt.GattService: current time is 95925006125
11-25 12:41:56.721  4508  4596 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -88, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -87, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -81, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -91, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -88, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 12:41:56.722  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 12:41:56.723  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 12:41:56.723  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 12:41:56.723  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-25 12:41:56.723  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 12:41:56.723  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-25 12:41:56.729  4508  4596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 12:41:56.729  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:41:56.729  4508  4599 D BtGatt.ScanManager: stopping BLe Batch
11-25 12:41:56.734  3836  5554 W CronetSyncConnectionRcs: Upload content type not set.
11-25 12:41:56.734  4508  4596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 12:41:56.734  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:41:56.735  4508  4599 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 12:41:56.740  4508  4596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 12:41:56.740  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:41:56.797  4723  4776 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-25 12:41:56.797  4723  4723 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-25 12:41:57.170  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 12:42:00.010   929   929 I ActivityManager: Killing 5302:com.android.chrome/u0a39 (adj 15): empty #17
,11-25 12:42:01.518   929  2827 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 12:42:01.704  5506  5553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 12:42:01.710  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 12:42:01.711  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 12:42:01.728  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 12:42:01.730  5506  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 12:42:01.730  5506  5553 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 12:42:01.731  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:42:01.731  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 12:42:01.731  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 12:42:01.731  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:42:01.731  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 12:42:01.737  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:01.738  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 12:42:01.738  5506  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 12:42:01.738  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 12:42:01.741  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:01.745  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.745  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 12:42:01.747  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 12:42:01.747  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 12:42:01.747  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 12:42:01.751  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.751  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 12:42:01.752  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 12:42:01.752  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 12:42:01.752  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 12:42:01.752  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.753  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:42:01.756  4508  4751 D BtGatt.GattService: registerClient() - UUID=3aeb74d2-6581-4cc1-a6e3-1601a65153aa
11-25 12:42:01.756  4508  4596 D BtGatt.GattService: onClientRegistered() - UUID=3aeb74d2-6581-4cc1-a6e3-1601a65153aa, clientIf=5
,11-25 12:42:01.757  5506  5517 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 12:42:01.757  4508  4752 D BtGatt.GattService: start scan with filters
,11-25 12:42:01.760  4508  4599 D BtGatt.ScanManager: handling starting scan
11-25 12:42:01.761  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 12:42:01.761  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.761  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 12:42:01.761  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.761  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 12:42:01.761  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 12:42:01.761  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.761  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 12:42:01.762  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 12:42:01.762  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.762  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.762  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.762  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 12:42:01.763  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-25 12:42:01.763  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.766  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.766  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:42:01.766  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.766  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.766  5506  5553 I io.jxcore.node.ConnectionHelper: start: OK
11-25 12:42:01.766  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 12:42:01.767  4508  4596 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 12:42:01.767  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.768  4508  4599 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 12:42:01.769  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.769  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.769  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.769  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 12:42:01.770  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:42:01.770  5506  5553 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 12:42:01.770  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:01.770  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 12:42:01.770  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:42:01.770  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 12:42:01.770  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:01.770  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 12:42:01.770  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 12:42:01.771  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.771  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 12:42:01.771  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 12:42:01.771  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.771  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.771  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.771  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 12:42:01.771  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.772  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:42:01.772  4508  4752 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 12:42:01.772  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 12:42:01.773  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:42:01.773  4508  4596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 12:42:01.773  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.773  4508  4599 D BtGatt.ScanManager: Starting BLE batch scan
11-25 12:42:01.773  4508  4599 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 12:42:01.774  4508  4521 D BtGatt.GattService: stopScan() - queue size =1
,11-25 12:42:01.775  4508  4520 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 12:42:01.775  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 12:42:01.775  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.775  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 12:42:01.775  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.775  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.775  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.775  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.776  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 12:42:01.776  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.776  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.776  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.776  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 12:42:01.776  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 12:42:01.777  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:42:01.777  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.778  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.778  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:42:01.778  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.778  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.778  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:01.778  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:42:01.778  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:42:01.778  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:42:01.778  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:42:01.778  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:01.778  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 12:42:01.778  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
,11-25 12:42:01.778  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.778  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:01.779  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 12:42:01.779  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:01.779  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 12:42:01.779  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:01.779  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.779  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 12:42:01.779  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.779  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.779  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:42:01.779  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.780  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.782  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.782  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.782  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.783  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.783  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.784  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.784  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.784  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.784  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:01.784  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:01.784  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:01.784  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:01.784  4508  4596 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 12:42:01.784  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.785  5506  5553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 12:42:01.787  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 12:42:01.787  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 12:42:01.790  4508  4596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 12:42:01.790  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.791  4508  4599 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 12:42:01.793  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 12:42:01.794  5506  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 12:42:01.794  5506  5553 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 12:42:01.794  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:42:01.794  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 12:42:01.795  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 12:42:01.795  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:42:01.795  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 12:42:01.795  4508  4596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 12:42:01.795  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.795  4508  4596 E BtGatt.ContextMap: Context not found for ID 5
11-25 12:42:01.797  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:01.797  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 12:42:01.798  5506  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 12:42:01.798  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 12:42:01.799  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:01.801  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.801  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 12:42:01.801  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 12:42:01.801  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 12:42:01.801  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 12:42:01.801  4508  4596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 12:42:01.802  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.802  4508  4599 D BtGatt.ScanManager: stopping BLe Batch
,11-25 12:42:01.804  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.804  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 12:42:01.804  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 12:42:01.804  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 12:42:01.804  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 12:42:01.804  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.805  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:42:01.806  4508  4596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 12:42:01.806  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.807  4508  4599 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 12:42:01.807  4508  4752 D BtGatt.GattService: registerClient() - UUID=bc61ceac-76c5-492e-b9c6-dc0b76566b74
11-25 12:42:01.808  4508  4596 D BtGatt.GattService: onClientRegistered() - UUID=bc61ceac-76c5-492e-b9c6-dc0b76566b74, clientIf=5
,11-25 12:42:01.808  5506  5517 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 12:42:01.808  4508  4520 D BtGatt.GattService: start scan with filters
,11-25 12:42:01.810  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 12:42:01.811  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.811  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 12:42:01.811  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.811  4508  4596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 12:42:01.811  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 12:42:01.811  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.811  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 12:42:01.811  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.811  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 12:42:01.811  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 12:42:01.811  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.811  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-25 12:42:01.811  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.811  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 12:42:01.812  4508  4599 D BtGatt.ScanManager: handling starting scan
11-25 12:42:01.813  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 12:42:01.813  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.815  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.815  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:42:01.815  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:01.816  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:01.816  5506  5553 I io.jxcore.node.ConnectionHelper: start: OK
,11-25 12:42:01.816  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.817  4508  4596 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 12:42:01.817  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:42:01.818  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.818  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.818  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:42:01.818  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 12:42:01.818  4508  4599 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 12:42:01.823  4508  4596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-25 12:42:01.823  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:01.823  4508  4599 D BtGatt.ScanManager: Starting BLE batch scan
11-25 12:42:01.823  4508  4599 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 12:42:01.831  4508  4596 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 12:42:01.831  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:42:01.835  4508  4596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 12:42:01.836  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:42:02.319  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 12:42:02.319  5506  5506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:42:02.319  5506  5506 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 12:42:04.706   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 12:42:04.712   929  2842 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-25 12:42:06.816  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:42:06.816  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 12:42:06.817  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-25 12:42:06.817  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 12:42:06.817  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-25 12:42:06.817  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:06.817  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 12:42:06.817  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 12:42:06.818  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:06.818  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 12:42:06.818  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 12:42:06.818  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.819  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.820  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.820  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 12:42:06.820  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.823  5506  5553 D BluetoothAdapter: STATE_ON
,11-25 12:42:06.824  4508  4520 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 12:42:06.825  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 12:42:06.826  4508  4599 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 12:42:06.827  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:42:06.828  4508  4521 D BtGatt.GattService: stopScan() - queue size =1
,11-25 12:42:06.830  4508  4752 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 12:42:06.831  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 12:42:06.831  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.832  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 12:42:06.832  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.832  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.832  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.833  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.833  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 12:42:06.833  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.833  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:06.833  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:06.833  4508  4508 D BtGatt.ScanManager: awakened up at time 106038
11-25 12:42:06.833  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 12:42:06.834  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 12:42:06.841  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:42:06.841  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:06.843  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.843  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:42:06.843  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.843  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:06.844  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:42:06.844  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:42:06.844  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 12:42:06.844  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.844  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 12:42:06.844  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 12:42:06.844  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.845  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.845  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.845  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:42:06.845  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.845  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.847  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.848  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:42:06.848  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 12:42:06.858  4508  4596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-25 12:42:06.858  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:06.858  4508  4596 D BtGatt.GattService: current time is 106063007848
11-25 12:42:06.859  4508  4596 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 96, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -84, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -89, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 12:42:06.859  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-25 12:42:06.859  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 12:42:06.860  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-25 12:42:06.860  4508  4596 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-25 12:42:06.868  4508  4596 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 12:42:06.868  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:06.868  4508  4599 D BtGatt.ScanManager: stopping BLe Batch
,11-25 12:42:06.874  4508  4596 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 12:42:06.874  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:42:06.874  4508  4599 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 12:42:06.880  4508  4596 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 12:42:06.881  4508  4596 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:42:07.346  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 12:42:07.346  5506  5506 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:07.346  5506  5506 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 12:42:07.728   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 12:42:07.734   929  2842 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-25 12:42:11.845  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:42:11.846  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.846  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.846  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.846  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:42:11.846  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:42:11.847  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:11.847  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:11.847  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.847  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.847  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:11.847  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 12:42:11.851  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.851  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.856  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.856  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.856  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.857  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.857  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.857  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.857  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
,11-25 12:42:11.858  5506  5553 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-25 12:42:11.860  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:11.860  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.860  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 12:42:11.861  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.861  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:11.861  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
,11-25 12:42:11.861  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:11.861  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.861  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:11.862  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.862  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.864  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.864  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.864  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.865  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 12:42:11.865  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.865  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.865  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
,11-25 12:42:11.867  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 12:42:11.867  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:11.867  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 12:42:11.868  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.868  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.868  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.868  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
,11-25 12:42:11.868  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.868  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.868  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:11.869  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.869  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.871  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.871  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.871  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.871  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.872  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.872  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.872  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
,11-25 12:42:11.873  5506  5553 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-25 12:42:11.874  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:11.874  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.874  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.874  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 12:42:11.874  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.874  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:11.874  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.875  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.875  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:11.875  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.875  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.877  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.878  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.878  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.878  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 12:42:11.878  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.878  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.878  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.880  5506  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-25 12:42:11.880  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:11.880  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.880  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.881  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.881  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.881  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
,11-25 12:42:11.881  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.881  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.881  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:11.881  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.882  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.884  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.884  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.884  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.884  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.884  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.884  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.884  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.886  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 12:42:11.886  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 12:42:11.887  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 12:42:11.887  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 12:42:11.887  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 12:42:11.887  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 12:42:11.887  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-25 12:42:11.887  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 12:42:11.887  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 12:42:11.887  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:11.888  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.888  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 12:42:11.888  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.888  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.888  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:11.888  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.888  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.888  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:11.888  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.889  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.897  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.897  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.897  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.897  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.897  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.897  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.898  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
,11-25 12:42:11.899  5506  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 12:42:11.900  5506  5553 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 12:42:11.900  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-25 12:42:11.910  5506  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-25 12:42:11.911  5506  5553 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 12:42:11.911  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 12:42:11.912  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 12:42:11.913  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 12:42:11.913  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 12:42:11.913  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 12:42:11.913  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 12:42:11.913  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-25 12:42:11.913  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 12:42:11.913  5506  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 12:42:11.913  5506  5553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 12:42:11.914  5506  5553 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 12:42:11.914  5506  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 12:42:11.914  5506  5553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 12:42:11.914  5506  5553 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-25 12:42:11.914  5506  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 12:42:11.914  5506  5553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 12:42:11.914  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-25 12:42:11.918  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-25 12:42:11.919  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 12:42:11.919  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-25 12:42:11.920  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-25 12:42:11.920  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-25 12:42:11.920  5506  5553 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 12:42:11.920  5506  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-25 12:42:11.921  5506  5553 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 12:42:11.921  5506  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-25 12:42:11.921  5506  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-25 12:42:11.922  5506  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-25 12:42:11.922  5506  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-25 12:42:11.922  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:42:11.923  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.923  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.923  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.923  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.923  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-25 12:42:11.925  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:11.925  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.926  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
,11-25 12:42:11.926  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:11.926  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.926  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.926  5506  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-25 12:42:11.926  5506  5559 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 12:42:11.927  5506  5558 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-25 12:42:11.927  5506  5558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:11.927  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.927  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.927  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.927  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.927  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.927  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:11.927  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
,11-25 12:42:11.928  4520  4520 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32250]" dev="sockfs" ino=32250 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 12:42:11.928  4520  4520 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32250]" dev="sockfs" ino=32250 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 12:42:11.928  5506  5553 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 12:42:11.929  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:11.929  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.929  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.929  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.929  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.930  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:11.930  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.930  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.930  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:11.930  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.930  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.931  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.931  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.931  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.931  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.931  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.931  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.931  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.932  5506  5553 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-25 12:42:11.932  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:11.933  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.933  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.933  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.933  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:11.933  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:11.933  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.933  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.933  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:11.935  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.935  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.936  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.936  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.936  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.936  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.936  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 12:42:11.936  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.937  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.937  5506  5553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 12:42:11.937  5506  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 12:42:11.937  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 12:42:11.937  5506  5553 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-25 12:42:11.938  5506  5553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 12:42:11.938  5506  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 12:42:11.938  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 12:42:11.938  5506  5553 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,11-25 12:42:11.938  5506  5553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 12:42:11.938  5506  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 12:42:11.938  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 12:42:11.938  5506  5553 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-25 12:42:11.938  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:42:11.938  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:11.938  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:11.938  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:11.938  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.938  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
,11-25 12:42:11.938  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.938  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.938  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:11.939  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.939  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.940  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.940  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:11.940  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:11.940  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:11.940  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:11.940  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.940  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.941  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 12:42:11.941  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:11.941  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:11.941  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:11.941  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:11.941  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:13.781   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 12:42:14.272   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 12:42:14.273   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 12:42:16.942  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:16.942  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.943  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:16.943  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:16.943  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:16.943  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:16.943  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:16.943  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:16.944  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 12:42:16.944  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:16.944  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:16.944  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:16.944  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.945  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:16.945  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.945  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.948  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.949  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.949  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.950  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:16.950  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:16.950  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:16.950  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.955  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-25 12:42:16.957  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:42:16.957  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 12:42:16.962  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-25 12:42:16.964  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-25 12:42:16.964  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-25 12:42:16.964  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-25 12:42:16.964  5506  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-25 12:42:16.965  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-25 12:42:16.965  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 12:42:16.965  5506  5506 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-25 12:42:16.966  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 12:42:16.966  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-25 12:42:16.966  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 12:42:16.966  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-25 12:42:16.966  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 12:42:16.966  5506  5560 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:16.967  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 12:42:16.967  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-25 12:42:16.967  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:16.967  5506  5506 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 12:42:16.967  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:16.967  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 12:42:16.968  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.968  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 12:42:16.968  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 12:42:16.968  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.970  5506  5560 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 12:42:16.970  5506  5560 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-25 12:42:16.970  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.970  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:42:16.970  5506  5560 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-25 12:42:16.968  4521  4521 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33080]" dev="sockfs" ino=33080 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 12:42:16.970  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.970  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.970  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.970  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:42:16.971  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:16.971  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:42:16.971  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:16.968  4521  4521 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33080]" dev="sockfs" ino=33080 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 12:42:16.971  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:42:16.971  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:16.971  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:16.971  5506  5506 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-25 12:42:16.971  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:16.971  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:16.971  5506  5506 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:16.971  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:16.971  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.971  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:16.972  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.972  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.974  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.974  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.974  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.974  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:16.974  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:16.974  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:16.974  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.976  5506  5553 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-25 12:42:16.977  5506  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 12:42:16.977  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 12:42:16.977  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 12:42:16.977  5506  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 12:42:16.977  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:42:16.977  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:16.977  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:16.978  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:16.978  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:42:16.978  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:16.978  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:16.978  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.978  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:16.978  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.978  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.981  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.981  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.981  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.982  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 12:42:16.982  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:16.982  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:16.982  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
,11-25 12:42:16.988  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:42:16.989  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:16.989  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:16.989  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:16.989  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:16.989  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:16.989  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:16.989  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.989  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:16.989  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.990  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.991  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.991  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.991  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.991  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:16.991  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:16.991  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:16.991  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.993  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 12:42:16.993  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:42:16.993  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:42:16.994  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:42:16.994  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:42:16.994  5506  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7730198 not in the list
11-25 12:42:16.994  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:16.994  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.994  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:16.994  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.994  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.995  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.996  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:42:16.996  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:42:16.996  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:42:16.996  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:42:16.996  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:16.996  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a042df1 not in the list
11-25 12:42:16.997  5506  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-25 12:42:16.997  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 12:42:16.997  5506  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-25 12:42:16.997  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-25 12:42:16.997  5506  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-25 12:42:16.998  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 12:42:17.000  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 12:42:17.000  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-25 12:42:17.001  5506  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-25 12:42:17.001  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 12:42:17.001  5506  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 12:42:17.001  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-25 12:42:17.002  5506  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-25 12:42:17.002  5506  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-25 12:42:17.002  5506  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-25 12:42:17.003  5506  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-25 12:42:17.003  5506  5553 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-25 12:42:17.003  5506  5553 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-25 12:42:17.003  5506  5553 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-25 12:42:17.003  5506  5553 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-25 12:42:17.005  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:42:17.005  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cab886 added. We now have 3 listener(s)
11-25 12:42:17.005  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:42:17.007  5506  5553 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 12:42:17.008   929  3750 D WifiService: setWifiEnabled: true pid=5506, uid=10077
,11-25 12:42:17.008   929  3750 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 12:42:17.057  4508  4702 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-25 12:42:17.057  4508  4733 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-25 12:42:17.058  5506  5558 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-25 12:42:17.058  5506  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 12:42:17.058  5506  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-25 12:42:17.471  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 12:42:19.274   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:19.835   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-25 12:42:20.275   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:21.276   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:22.013  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 12:42:22.014  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2d9547 added. We now have 4 listener(s)
11-25 12:42:22.014  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:42:22.023  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:22.023  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f2d9547 removed from the list
,11-25 12:42:22.023  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:22.024  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 12:42:22.025  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ce6174 added. We now have 4 listener(s)
,11-25 12:42:22.025  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:42:22.027  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:42:22.027  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ce6174 removed from the list
,11-25 12:42:22.027  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:22.029  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:42:22.029  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e49069d added. We now have 4 listener(s)
,11-25 12:42:22.030  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:42:22.034   929  3289 D WifiService: setWifiEnabled: false pid=5506, uid=10077
11-25 12:42:22.035   929  3289 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 12:42:22.042   929  2827 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 12:42:22.042   929  2827 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-25 12:42:22.042   929  2827 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 12:42:22.042   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 12:42:22.048  4508  4592 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 12:42:22.048  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 12:42:22.048  4508  4592 D BluetoothAdapterProperties: Setting state to 13
,11-25 12:42:22.048  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 12:42:22.048  4508  4592 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 12:42:22.049  4508  4592 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 12:42:22.052  4508  4592 I BluetoothAdapterState: Entering PendingCommandState
11-25 12:42:22.055  4508  4596 D BluetoothAdapterProperties: Scan Mode:20
11-25 12:42:22.056  4508  4592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 12:42:22.060   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-25 12:42:22.061   929  5260 D DhcpClient: Clearing IP address
11-25 12:42:22.061  4508  4508 D BluetoothMapService: onReceive
11-25 12:42:22.061  4508  4508 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 12:42:22.061  4508  4508 D BluetoothMapService: STATE_TURNING_OFF
11-25 12:42:22.062  4508  4508 D BluetoothMapService: MAP Service closeService in
11-25 12:42:22.062  4508  4508 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 12:42:22.062  4508  4508 D ObexServerSockets0: shutdown(block = true)
11-25 12:42:22.062  4508  4754 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-25 12:42:22.063  4508  4508 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 12:42:22.063  4508  4508 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 12:42:22.063  4508  4733 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 12:42:22.063  4508  4755 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 12:42:22.063  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 12:42:22.064  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 12:42:22.065  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 12:42:22.065  5506  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 12:42:22.065  5506  5553 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 12:42:22.066  3453  5317 V NativeCrypto: Read error: ssl=0x7f92c70500: I/O error during system call, Connection timed out
11-25 12:42:22.067  4508  4508 I BtOppRfcommListener: stopping Accept Thread
,11-25 12:42:22.068  4508  5192 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-25 12:42:22.068  4508  5192 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 12:42:22.069  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:22.070  3453  5317 V NativeCrypto: SSL shutdown failed: ssl=0x7f92c70500: I/O error during system call, Broken pipe
11-25 12:42:22.072  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:22.073   929  3289 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-25 12:42:22.073   929  5258 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-25 12:42:22.075  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:22.075   507   921 D CommandListener: Setting iface cfg
11-25 12:42:22.076   929   942 I ActivityManager: Start proc 5564:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-25 12:42:22.076   929  5258 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-25 12:42:22.077   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-25 12:42:22.078   929  5261 D DhcpClient: Receive thread stopped
11-25 12:42:22.078   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 12:42:22.079  4508  4508 D HeadsetService: Received stop request...Stopping profile...
11-25 12:42:22.080   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:22.080   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:22.080  3657  3676 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:22.081  3009  3865 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:22.081  4508  4508 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:22.082  4508  4508 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:22.082  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.082   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:22.082  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:22.082  4508  4508 D A2dpService: Received stop request...Stopping profile...
11-25 12:42:22.083  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:22.083  4508  4746 D A2dpStateMachine: Exit Disconnected: -1
11-25 12:42:22.083   929  2842 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 12:42:22.084   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 12:42:22.084  3009  3009 D HeadsetProfile: Bluetooth service disconnected
11-25 12:42:22.084   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-25 12:42:22.089   533   533 E Parcel  : Reading a NULL string not supported here.
11-25 12:42:22.090  3009  3009 D BluetoothA2dp: Proxy object disconnected
11-25 12:42:22.090   929   929 D RttService: SCAN_AVAILABLE : 1
,11-25 12:42:22.091   929   929 D BluetoothA2dp: Proxy object disconnected
11-25 12:42:22.091   929  2950 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 12:42:22.091   929  2842 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-25 12:42:22.093  4508  4508 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 12:42:22.093  3620  3778 W QCNEJ   : |CORE| network lost: 100
11-25 12:42:22.093  4508  4508 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 12:42:22.093  4508  4596 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 12:42:22.093  4508  4702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:22.093  4508  4702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:22.093  4508  4702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:22.094  3620  3778 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 12:42:22.094  4508  4596 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 12:42:22.094  4508  4508 D HidService: Received stop request...Stopping profile...
11-25 12:42:22.094  4508  4508 D HidService: Stopping Bluetooth HidService
,11-25 12:42:22.096  4508  4508 D HealthService: Received stop request...Stopping profile...
11-25 12:42:22.096   929  2827 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 12:42:22.098  4508  4508 D PanService: Received stop request...Stopping profile...
,11-25 12:42:22.099  4508  4508 V BluetoothAdapterState: isTurningOff()=true
,11-25 12:42:22.099  4508  4508 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:22.099  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.099  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:22.100  4508  4508 D BluetoothMapService: Received stop request...Stopping profile...
11-25 12:42:22.100  4508  4508 D BluetoothMapService: stop()
11-25 12:42:22.101  4508  4508 D BluetoothMapAppObserver: deinitObservers()
11-25 12:42:22.101  4508  4508 D BluetoothMapAppObserver: removeReceiver()
11-25 12:42:22.102  3009  3009 D BluetoothInputDevice: Proxy object disconnected
11-25 12:42:22.102  3009  3009 D HidProfile: Bluetooth service disconnected
,11-25 12:42:22.102   929  2827 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 12:42:22.102  3009  3009 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 12:42:22.102  3009  3009 D PanProfile: Bluetooth service disconnected
11-25 12:42:22.102  3009  3009 D BluetoothMap: Proxy object disconnected
11-25 12:42:22.102  3009  3009 D MapProfile: Bluetooth service disconnected
11-25 12:42:22.103  4508  4702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:22.103  4508  4702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 12:42:22.103  4508  4702 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-25 12:42:22.103  4508  4702 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 12:42:22.103  4508  4508 D SapService: Received stop request...Stopping profile...
,11-25 12:42:22.103  4508  4702 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 12:42:22.103  4508  4508 V SapService: stop()
11-25 12:42:22.103  4508  4702 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 12:42:22.103  4508  4596 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 12:42:22.104  4508  4508 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:22.104  4508  4508 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:22.104  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.104  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 12:42:22.104  4508  4508 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 12:42:22.104  4508  4508 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:22.105  4508  4508 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 12:42:22.105  4508  4508 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.105  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 12:42:22.106  4508  4508 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 12:42:22.106  4508  4508 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 12:42:22.106  4508  4596 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 12:42:22.106  4508  4596 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 12:42:22.106  4508  4508 D BluetoothMapService: MAP Service closeService in
11-25 12:42:22.106  4508  4508 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:22.106  4508  4508 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:22.106  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.106  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:22.107  4508  4508 D BluetoothMapService: cleanup()
11-25 12:42:22.107  4508  4508 D BluetoothMapService: MAP Service closeService in
11-25 12:42:22.107  4508  4508 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:22.107  4508  4508 V BluetoothAdapterState: isTurningOn()=false
,11-25 12:42:22.107  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.107  4508  4508 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:22.107  4508  4592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 12:42:22.108  4508  4592 D BluetoothAdapterProperties: Setting state to 15
11-25 12:42:22.108  4508  4592 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 12:42:22.108  4508  4592 I BluetoothAdapterState: Entering BleOnState
11-25 12:42:22.114   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:22.114  3009  3021 D BluetoothMap: onBluetoothStateChange: up=false
11-25 12:42:22.115  3009  3864 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 12:42:22.116   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:22.116  3657  3874 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:22.116   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 12:42:22.116  3009  3865 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 12:42:22.120   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:22.120  3009  3020 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 12:42:22.121  3009  3021 D BluetoothPan: onBluetoothStateChange on: false
11-25 12:42:22.122  3009  3864 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 12:42:22.122   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 12:42:22.122  4508  4592 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 12:42:22.123  4508  4592 D BluetoothAdapterProperties: Setting state to 16
11-25 12:42:22.123  4508  4592 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 12:42:22.123  4508  4592 D BluetoothAdapterProperties: onBleDisable
11-25 12:42:22.123  4508  4592 I BluetoothAdapterState: Entering PendingCommandState
11-25 12:42:22.123  4508  4593 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-25 12:42:22.126  4508  4702 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 12:42:22.126  4508  4702 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:22.126  4508  4596 D BluetoothAdapterProperties: Scan Mode:20
11-25 12:42:22.127  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:22.127  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 12:42:22.128  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:22.128  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 12:42:22.129  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:22.136   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 12:42:22.136   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-25 12:42:22.137   507   921 D TetherController: Setting IP forward enable = 0
,11-25 12:42:22.137   929  2842 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-25 12:42:22.137   929  2842 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 12:42:22.138  5564  5564 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-25 12:42:22.140   929  2827 D DhcpClient: doQuit
,11-25 12:42:22.140   929  2827 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 12:42:22.141   929  5260 D DhcpClient: onQuitting
11-25 12:42:22.141  3329  3329 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 12:42:22.142  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:22.142  5149  5149 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8c9922b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-25 12:42:22.142   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-25 12:42:22.146  4934  4956 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 12:42:22.143  3836  3836 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-25 12:42:22.147  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:22.147  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 12:42:22.148  4934  4956 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 12:42:22.148  4934  4956 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 12:42:22.148  4934  4956 E SarControlService: no key has been found,reset the power
11-25 12:42:22.148  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 12:42:22.148  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 12:42:22.148  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:22.148  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 12:42:22.148  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 12:42:22.149  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 12:42:22.149  4959  4959 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 12:42:22.150  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 12:42:22.150  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 12:42:22.150  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-25 12:42:22.151  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 12:42:22.151  4959  4959 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 12:42:22.151  3329  3329 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-25 12:42:22.154  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000ea03000000000000ffffffff]
11-25 12:42:22.154  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:42:22.154  4959  4973 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 12:42:22.154  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 12:42:22.154  4934  4944 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 12:42:22.156  3329  3329 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 12:42:22.158  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000eb03000000000000ffffffff]
11-25 12:42:22.158  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:42:22.158  4959  4973 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-25 12:42:22.158  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 12:42:22.159  4934  4945 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 12:42:22.168  5564  5564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 12:42:22.174   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@869b49d:true
,11-25 12:42:22.174  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:22.187  3329  3329 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-25 12:42:22.188   929  3739 I ActivityManager: Start proc 5593:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-25 12:42:22.196  5564  5564 D LocalBluetoothProfileManager: Adding local MAP profile
11-25 12:42:22.197   507   921 E Netd    : netlink response contains error (No such file or directory)
11-25 12:42:22.198   507   921 D TetherController: Setting IP forward enable = 0
11-25 12:42:22.199   929  2842 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-25 12:42:22.199   929  2842 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 12:42:22.199  3329  3329 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-25 12:42:22.200  5564  5564 D BluetoothMap: Create BluetoothMap proxy object
11-25 12:42:22.200   507   921 E FrameworkListener: read() failed (Connection reset by peer)
11-25 12:42:22.206  5564  5564 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 12:42:22.214  5564  5564 D DockEventReceiver: finishStartingService: stopping service
,11-25 12:42:22.222   929  3289 I ActivityManager: Killing 4363:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-25 12:42:22.237  5593  5593 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-25 12:42:22.276   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:22.301   929  2827 D wifi    : In wifi stop Hal
,11-25 12:42:22.302  4901  4901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 12:42:22.302   929  2827 D wifi    : halHandle = 0x7f91716680, mVM = 0x7fadd0d140, mCls = 0x100a02
11-25 12:42:22.302   929  3328 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 12:42:22.302   929  3328 D WifiHAL : Got a signal to exit!!!
11-25 12:42:22.302   929  3328 I WifiHAL : Exit wifi_event_loop
,11-25 12:42:22.303   929  2827 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 12:42:22.303   929  2827 E WifiHAL : Event processing terminated
11-25 12:42:22.303   929  2827 D wifi    : In wifi cleaned up handler
11-25 12:42:22.304   929  2827 I WifiHAL : Internal cleanup completed
11-25 12:42:22.304  3916  4100 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 12:42:22.305  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:22.325   929  3328 D wifi    : set interface wlan0 flags (DOWN)
,11-25 12:42:22.325   929  2827 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 12:42:22.332  4508  4596 I bt_hci  : shut_down
,11-25 12:42:22.336  4508  4600 D bt_hwcfg: hw_epilog_process
,11-25 12:42:22.336  4508  4600 I bt_vendor: low_power_mode_cb
,11-25 12:42:22.339  4508  4600 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-25 12:42:22.339  4508  4600 I bt_vendor: epilog_cb
11-25 12:42:22.339  4508  4600 I bt_hci  : epilog_finished_callback
11-25 12:42:22.341  4508  4596 I bt_hci_h4: hal_close
11-25 12:42:22.342  4508  4596 I bt_userial_vendor: device fd = 54 close
,11-25 12:42:22.410  5593  5593 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.410  5593  5593 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.410  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.411  5593  5593 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.411  5593  5593 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.411  5593  5593 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.k.d(PG:583)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.411  5593  5593 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.411  5593  5593 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.411  5593  5593 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:42:22.411  5593  5593 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:42:22.417  5564  5564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 12:42:22.422  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:22.429  3568  3568 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 12:42:22.433  3568  3568 D SystemUpdateService: onCreate
11-25 12:42:22.436  3568  3568 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 12:42:22.439  5564  5564 D DockEventReceiver: finishStartingService: stopping service
,11-25 12:42:22.444  3568  3568 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-25 12:42:22.450  4508  4593 D bt_stack_manager: event_shut_down_stack finished.
11-25 12:42:22.451  4508  4592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-25 12:42:22.452  4508  4592 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 12:42:22.452  4508  4508 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 12:42:22.453  4508  4508 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 12:42:22.453  4508  4508 D BtGatt.GattService: stop()
11-25 12:42:22.453  4508  4508 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 12:42:22.454  4508  4508 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:22.454  4508  4508 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:22.454  4508  4508 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:22.454  4508  4508 V BluetoothAdapterState: isBleTurningOff()=true
11-25 12:42:22.454  4508  4592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 12:42:22.455  4508  4592 D BluetoothAdapterProperties: Setting state to 10
11-25 12:42:22.455  4508  4592 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 12:42:22.455  4508  4592 I BluetoothAdapterState: Entering OffState
11-25 12:42:22.456   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-25 12:42:22.457  3568  5283 I iu.UploadsManager: num queued entries: 0
11-25 12:42:22.462  4508  4508 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-25 12:42:22.462  4508  4508 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 12:42:22.462  4508  4508 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 12:42:22.463  4508  4593 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 12:42:22.469  4508  4508 I art     : System.exit called, status: 0
11-25 12:42:22.469  4508  4508 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-25 12:42:22.481  3568  3568 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 12:42:22.483  3568  3568 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 12:42:22.489  3568  5283 I iu.UploadsManager: num updated entries: 0
,11-25 12:42:22.489  3568  5283 I iu.SyncManager: NEXT; no task
,11-25 12:42:22.490  3568  5626 I SystemUpdateService: active receiver: enabled
,11-25 12:42:22.493  3568  5626 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 12:42:22.494   929  3750 I ActivityManager: Start proc 5630:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-25 12:42:22.517   929  3759 I ActivityManager: Process com.android.bluetooth (pid 4508) has died
,11-25 12:42:22.527  5630  5630 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-25 12:42:22.528   929   946 D Tethering: InitialState.processMessage what=4
,11-25 12:42:22.531   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 12:42:22.532  3568  5626 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 12:42:22.535  3568  5626 I SystemUpdateService: now status is 0 (complete)
11-25 12:42:22.536  3568  5626 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 12:42:22.536  3568  5626 I SystemUpdateService: file has been verified
11-25 12:42:22.536  3568  5626 I SystemUpdateService: OTA package size = 21989297
,11-25 12:42:22.541  5630  5630 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 12:42:22.550  5630  5630 D SprintDMHelper: simOperator: 
11-25 12:42:22.550  5630  5630 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 12:42:22.559  3568  5626 I SystemUpdateService: showing system update notification
,11-25 12:42:22.562   929  3680 I ActivityManager: Start proc 5642:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-25 12:42:22.563   929  3680 I ActivityManager: Killing 5011:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-25 12:42:22.627   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 12:42:22.663  3568  3568 D SystemUpdateService: onDestroy
,11-25 12:42:22.665   929  3739 I ActivityManager: Killing 5337:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-25 12:42:22.714  4901  5656 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 12:42:22.724   929  3739 I ActivityManager: Start proc 5657:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-25 12:42:22.727   929  3667 I ActivityManager: Killing 5149:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-25 12:42:22.780  5657  5657 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-25 12:42:22.788   929  3739 I ActivityManager: Killing 3773:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-25 12:42:22.856  5593  5614 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-25 12:42:22.866   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d7ca7e6:true
,11-25 12:42:23.277   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:24.278   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 12:42:27.067   929  3667 D WifiService: setWifiEnabled: true pid=5506, uid=10077
,11-25 12:42:27.068   929  3667 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 12:42:27.076   507   921 D SoftapController: Softap fwReload - Ok
,11-25 12:42:27.084   507   921 D CommandListener: Setting iface cfg
11-25 12:42:27.084   507   921 D CommandListener: Trying to bring down wlan0
11-25 12:42:27.086   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-25 12:42:27.094   929  2827 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 12:42:27.650   929  2827 D wifi    : set interface wlan0 flags (UP)
,11-25 12:42:27.652   929  2827 I WifiHAL : Initializing wifi
11-25 12:42:27.652   929  2827 I WifiHAL : Creating socket
11-25 12:42:27.653   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 12:42:27.655   929  2827 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 12:42:27.655   929  2827 D wifi    : Did set static halHandle = 0x7f91716680
11-25 12:42:27.655   929  2827 D wifi    : halHandle = 0x7f91716680, mVM = 0x7fadd0d140, mCls = 0x19ba
11-25 12:42:27.655   929  2827 D wifi    : array field set
11-25 12:42:27.656   929  2827 I WifiNative-HAL: interface[0] = wlan0
,11-25 12:42:27.657   929  5674 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547900974720
,11-25 12:42:27.657   929  5674 D wifi    : waitForHalEvents called, vm = 0x7fadd0d140, obj = 0x19ba, env = 0x7f8ee94200
,11-25 12:42:27.715  5675  5675 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 12:42:27.759   929  2827 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 12:42:27.764  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:27.770  5675  5675 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 12:42:27.835  5675  5675 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-25 12:42:27.835  5675  5675 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 12:42:27.851   929  2827 D WifiConfigStore: Loading config and enabling all networks 
,11-25 12:42:27.853  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:27.853  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 12:42:27.853  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:27.853  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 12:42:27.887   929  2827 D WifiConfigStore: loaded 0 passpoint configs
,11-25 12:42:27.888   929  2827 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-25 12:42:27.888   929  2827 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 12:42:27.889   929  2827 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 12:42:27.890   929  2827 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-25 12:42:27.891   929  2827 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-25 12:42:27.892   929  2827 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 12:42:27.892   929  2827 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 12:42:27.892   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-25 12:42:27.893   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 12:42:27.893   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 12:42:27.893   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 12:42:27.893   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 12:42:27.897   929  2827 D WifiNative-HAL: Setting external_sim to 1
,11-25 12:42:27.897   929  2827 D wifi    : setting dfs flag to true, 0x7f96b3f980
11-25 12:42:27.897   929  2827 D WifiStateMachine: Setting OUI to DA-A1-19
,11-25 12:42:27.897  4901  4901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 12:42:27.897   929  2827 D wifi    : setting scan oui 0x7f96b3f980
11-25 12:42:27.897   929  2827 D WifiHAL : Sending mac address OUI
,11-25 12:42:27.901   929  2827 E native  : do suspend false
,11-25 12:42:27.912   929  2827 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 12:42:27.913   929   929 D RttService: SCAN_AVAILABLE : 3
11-25 12:42:27.913   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 12:42:27.913   929  2950 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 12:42:27.914   507   921 D CommandListener: Setting iface cfg
,11-25 12:42:27.919   929  2825 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-25 12:42:27.919   929  2825 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 12:42:27.929   929  2825 D WifiNative-HAL: p2pGetDeviceAddress
11-25 12:42:27.930   929  2825 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 12:42:27.936   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=127140 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-25 12:42:29.279   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:30.281   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:30.980  5675  5675 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 12:42:30.985  5675  5675 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 12:42:30.989  5675  5675 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 12:42:31.041   929  2827 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-25 12:42:31.043   929  2827 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-25 12:42:31.043   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 12:42:31.054   929  2827 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 12:42:31.088   929  2827 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 12:42:31.094  5675  5675 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 12:42:31.282   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:31.514  5675  5675 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 12:42:31.544  5675  5675 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 12:42:31.544  5675  5675 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 12:42:31.555   929  2827 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 12:42:31.555   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 12:42:31.555   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 12:42:31.572   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 12:42:31.585   507   921 D CommandListener: Setting iface cfg
,11-25 12:42:31.592   929  2827 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 12:42:31.598   929  5681 D DhcpClient: Receive thread started
,11-25 12:42:31.602   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 12:42:31.602   929  2827 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-25 12:42:31.602   929  2842 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 12:42:31.683   929  2827 E native  : do suspend false
,11-25 12:42:31.698   929  5680 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 12:42:31.727   929  5681 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-25 12:42:31.728   929  5680 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-25 12:42:31.730   929  5680 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 12:42:31.751   929  5681 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 12:42:31.752   929  5680 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 12:42:31.755   507   921 D CommandListener: Setting iface cfg
,11-25 12:42:31.760   929  2827 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 12:42:31.768   929  5680 D DhcpClient: Scheduling renewal in 86399s
,11-25 12:42:31.773   929  2827 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 12:42:31.775   929  2827 D WifiConfigStore: No blacklist allowed without epno enabled
11-25 12:42:31.776   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-25 12:42:31.777   929  2842 D ConnectivityService: Adding iface wlan0 to network 101
,11-25 12:42:31.785   929  2827 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 12:42:31.829   929  2842 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 12:42:31.829   929  2842 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 12:42:31.840   929  2842 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-25 12:42:31.842   929  2842 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-25 12:42:31.844   929  2842 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-25 12:42:31.851   929  2842 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 12:42:31.855   929  2842 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-25 12:42:31.855   929  2842 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-25 12:42:31.855   929  2842 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 12:42:31.855   929  2842 D ConnectivityService:    accepting network in place of null
11-25 12:42:31.855   929  2827 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-25 12:42:31.855   929  2827 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 12:42:31.856   929  2842 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 12:42:31.867   929  5679 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131071, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 12:42:31.879   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 12:42:31.902   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 12:42:31.905   929  2842 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 12:42:31.905   929  2842 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 12:42:31.905  3620  3778 W QCNEJ   : |CORE| network available: 101
11-25 12:42:31.906   929  2842 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-25 12:42:31.908   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-25 12:42:31.910  3620  3778 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-25 12:42:31.911  3620  3778 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 12:42:31.911  3620  3778 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-25 12:42:31.912  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 12:42:31.912  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 12:42:31.912  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:31.912  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 12:42:31.921  4934  4956 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 12:42:31.921  4934  4956 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 12:42:31.921  4934  4956 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 12:42:31.921  4934  4956 E SarControlService: no key has been found,reset the power
11-25 12:42:31.921  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 12:42:31.921  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 12:42:31.922  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 12:42:31.922  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 12:42:31.922  4959  4959 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 12:42:31.924  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-25 12:42:31.924  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 12:42:31.924  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 12:42:31.924  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 12:42:31.924  4959  4959 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 12:42:31.925  3836  3836 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-25 12:42:31.929  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000ec03000000000000ffffffff]
11-25 12:42:31.929  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:42:31.929  4959  4973 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 12:42:31.929  3568  3568 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 12:42:31.930  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000ed03000000000000ffffffff]
11-25 12:42:31.930  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:42:31.930  4959  4973 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-25 12:42:31.931   929  5678 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 12:42:31.933  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 12:42:31.933  4934  4944 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 12:42:31.934  3568  3568 D SystemUpdateService: onCreate
11-25 12:42:31.934  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 12:42:31.934  4934  4945 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 12:42:31.938  3568  3568 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 12:42:31.948  3568  3568 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 12:42:31.952  3568  5283 I iu.UploadsManager: num queued entries: 0
,11-25 12:42:31.953  3568  5283 I iu.UploadsManager: num updated entries: 0
11-25 12:42:31.953  3568  5283 I iu.SyncManager: NEXT; no task
,11-25 12:42:31.955  3568  5691 I SystemUpdateService: active receiver: enabled
,11-25 12:42:31.959  3568  3568 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 12:42:31.960  3568  3568 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 12:42:31.962  5630  5630 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 12:42:31.965  5630  5630 D SprintDMHelper: simOperator: 
11-25 12:42:31.965  5630  5630 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 12:42:31.984   929  5678 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 11:42:31 GMT], X-Android-Received-Millis=[1480074151983], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480074151958]}
,11-25 12:42:31.984   929  2842 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 12:42:31.984   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-25 12:42:31.985   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-25 12:42:31.986   929  2842 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 12:42:31.986  3568  5691 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 12:42:31.998  3568  5691 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-25 12:42:31.998  3568  5691 I SystemUpdateService: now status is 0 (complete)
11-25 12:42:31.998  3568  5691 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 12:42:31.999  3568  5691 I SystemUpdateService: file has been verified
11-25 12:42:31.999  3568  5691 I SystemUpdateService: OTA package size = 21989297
,11-25 12:42:32.004  3568  5691 I SystemUpdateService: showing system update notification
,11-25 12:42:32.012   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 12:42:32.013  3568  3568 D SystemUpdateService: onDestroy
,11-25 12:42:32.071  4901  5696 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 12:42:32.074   929  3680 D WifiService: setWifiEnabled: false pid=5506, uid=10077
,11-25 12:42:32.074   929  3680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 12:42:32.075   929  2827 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-25 12:42:32.075   929  2827 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 12:42:32.076   929  2827 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 12:42:32.076   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 12:42:32.083   929  5680 D DhcpClient: Clearing IP address
11-25 12:42:32.083   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-25 12:42:32.085   507   921 D CommandListener: Setting iface cfg
,11-25 12:42:32.095   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-25 12:42:32.095   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-25 12:42:32.101   533   533 E Parcel  : Reading a NULL string not supported here.
11-25 12:42:32.102   929  2842 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-25 12:42:32.103   929   929 D RttService: SCAN_AVAILABLE : 1
11-25 12:42:32.103  3620  3778 W QCNEJ   : |CORE| network lost: 101
11-25 12:42:32.104   929  2950 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 12:42:32.104  3620  3778 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 12:42:32.105   929  5681 D DhcpClient: Receive thread stopped
11-25 12:42:32.106   929  2827 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-25 12:42:32.108   929  2827 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 12:42:32.128   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 12:42:32.148   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 12:42:32.149   507   921 D CommandListener: Clearing all IP addresses on wlan0
11-25 12:42:32.149   929  2842 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 12:42:32.149   929  2842 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 12:42:32.151   929   946 D Tethering: MasterInitialState.processMessage what=3
11-25 12:42:32.154   929  2827 D DhcpClient: doQuit
11-25 12:42:32.154   929  2827 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 12:42:32.155   929  5680 D DhcpClient: onQuitting
11-25 12:42:32.155  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:32.155  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 12:42:32.155  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:32.155  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 12:42:32.155  5675  5675 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 12:42:32.156  3836  3836 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-25 12:42:32.161  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:32.161  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 12:42:32.161  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:32.161  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 12:42:32.161  3568  3568 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 12:42:32.163  4934  4956 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 12:42:32.163  4934  4956 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 12:42:32.163  4934  4956 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 12:42:32.164  4934  4956 E SarControlService: no key has been found,reset the power
11-25 12:42:32.164  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 12:42:32.164  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 12:42:32.164  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 12:42:32.164  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 12:42:32.164  4959  4959 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-25 12:42:32.166  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-25 12:42:32.166  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 12:42:32.166  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 12:42:32.166  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 12:42:32.166  4959  4959 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 12:42:32.169  3568  3568 D SystemUpdateService: onCreate
11-25 12:42:32.171  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000ee03000000000000ffffffff]
11-25 12:42:32.171  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:42:32.171  4959  4973 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 12:42:32.171  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 12:42:32.171  4934  4945 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 12:42:32.173  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000ef03000000000000ffffffff]
11-25 12:42:32.173  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:42:32.173  4959  4973 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-25 12:42:32.174  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 12:42:32.174  4934  4944 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 12:42:32.175  3568  3568 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 12:42:32.177  5675  5675 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 12:42:32.183  5675  5675 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 12:42:32.184  3568  3568 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-25 12:42:32.189  3568  5283 I iu.UploadsManager: num queued entries: 0
,11-25 12:42:32.189  3568  5283 I iu.UploadsManager: num updated entries: 0
11-25 12:42:32.190  3568  5283 I iu.SyncManager: NEXT; no task
11-25 12:42:32.182  3568  5709 I SystemUpdateService: active receiver: enabled
,11-25 12:42:32.193  3568  3568 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 12:42:32.194  3568  3568 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 12:42:32.196  5630  5630 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 12:42:32.200  5630  5630 D SprintDMHelper: simOperator: 
11-25 12:42:32.200  5630  5630 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 12:42:32.209  3568  5709 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 12:42:32.212   507   921 E Netd    : netlink response contains error (No such file or directory)
,11-25 12:42:32.212  4901  5714 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-25 12:42:32.213   929  2842 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-25 12:42:32.215  5675  5675 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 12:42:32.218  3568  5709 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-25 12:42:32.218  3568  5709 I SystemUpdateService: now status is 0 (complete)
,11-25 12:42:32.218  3568  5709 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-25 12:42:32.220  3568  5709 I SystemUpdateService: file has been verified
,11-25 12:42:32.222  5675  5675 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 12:42:32.225  3568  5709 I SystemUpdateService: OTA package size = 21989297
,11-25 12:42:32.233  3568  5709 I SystemUpdateService: showing system update notification
,11-25 12:42:32.241   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 12:42:32.242  3568  3568 D SystemUpdateService: onDestroy
,11-25 12:42:32.282   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:32.324   929  2827 D wifi    : In wifi stop Hal
,11-25 12:42:32.324   929  2827 D wifi    : halHandle = 0x7f91716680, mVM = 0x7fadd0d140, mCls = 0x19ba
11-25 12:42:32.324   929  5674 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 12:42:32.324   929  5674 D WifiHAL : Got a signal to exit!!!
11-25 12:42:32.324   929  5674 I WifiHAL : Exit wifi_event_loop
11-25 12:42:32.325   929  2827 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-25 12:42:32.325   929  2827 E WifiHAL : Event processing terminated
11-25 12:42:32.325   929  2827 D wifi    : In wifi cleaned up handler
11-25 12:42:32.325   929  2827 I WifiHAL : Internal cleanup completed
,11-25 12:42:32.329  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:32.330  4901  4901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 12:42:32.331  3916  4100 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 12:42:32.355   929  5674 D wifi    : set interface wlan0 flags (DOWN)
,11-25 12:42:32.355   929  2827 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 12:42:32.561   929   946 D Tethering: InitialState.processMessage what=4
,11-25 12:42:32.566   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 12:42:32.905   929  2842 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 12:42:33.283   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:34.283   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 12:42:37.112   929   946 I ActivityManager: Start proc 5716:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 12:42:37.204  5716  5716 D AdapterServiceConfig: Adding HeadsetService
,11-25 12:42:37.204  5716  5716 D AdapterServiceConfig: Adding A2dpService
11-25 12:42:37.204  5716  5716 D AdapterServiceConfig: Adding HidService
11-25 12:42:37.204  5716  5716 D AdapterServiceConfig: Adding HealthService
11-25 12:42:37.204  5716  5716 D AdapterServiceConfig: Adding PanService
,11-25 12:42:37.205  5716  5716 D AdapterServiceConfig: Adding GattService
11-25 12:42:37.205  5716  5716 D AdapterServiceConfig: Adding BluetoothMapService
11-25 12:42:37.205  5716  5716 D AdapterServiceConfig: Adding SapService
,11-25 12:42:37.216   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5390f5:true
,11-25 12:42:37.216  5716  5716 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 12:42:37.219  5716  5716 I bt_bluedroid: init
,11-25 12:42:37.219  5716  5728 I BluetoothAdapterState: Entering OffState
,11-25 12:42:37.221  5716  5729 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 12:42:37.221  5716  5729 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 12:42:37.221  5716  5729 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 12:42:37.221  5716  5729 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 12:42:37.222  5716  5716 I bt_bluedroid: get_profile_interface socket
,11-25 12:42:37.223  5716  5732 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 12:42:37.224  5716  5716 I bt_bluedroid: get_profile_interface sdp
11-25 12:42:37.225  5716  5732 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 12:42:37.229  5716  5727 I bt_bluedroid: config_hci_snoop_log
,11-25 12:42:37.230   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 12:42:37.234  5716  5728 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 12:42:37.234  5716  5728 D BluetoothAdapterProperties: Setting state to 14
11-25 12:42:37.234  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 12:42:37.236  5716  5728 D BluetoothBondStateMachine: make
,11-25 12:42:37.238  5716  5733 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 12:42:37.240  5716  5728 I BluetoothAdapterState: Entering PendingCommandState
,11-25 12:42:37.242  5716  5716 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 12:42:37.244  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:37.244  5716  5716 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 12:42:37.245  5716  5716 D BtGatt.GattService: Received start request. Starting profile...
11-25 12:42:37.245  5716  5716 D BtGatt.GattService: start()
11-25 12:42:37.245  5716  5716 I bt_bluedroid: get_profile_interface gatt
11-25 12:42:37.246  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:37.246  5716  5716 D BtGatt.AdvertiseManager: advertise manager created
,11-25 12:42:37.251  5716  5716 V BluetoothAdapterState: isTurningOff()=false
,11-25 12:42:37.251  5716  5716 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:37.251  5716  5716 V BluetoothAdapterState: isBleTurningOn()=true
11-25 12:42:37.251  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:37.251  5716  5728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 12:42:37.252  5716  5728 I bt_bluedroid: bt_bluedroid
,11-25 12:42:37.253  5716  5729 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 12:42:37.253  5716  5729 I bt_hci  : start_up
,11-25 12:42:37.259  5716  5729 I bt_vendor: alloc value 0xf3bf9871
,11-25 12:42:37.259  5716  5729 I bt_vendor: init
11-25 12:42:37.259  5716  5729 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 12:42:37.259  5716  5729 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 12:42:37.366  5716  5729 D bt_hci  : start_up starting async portion
11-25 12:42:37.366  5716  5736 I bt_hci  : event_finish_startup
11-25 12:42:37.367  5716  5736 I bt_hci_h4: hal_open
11-25 12:42:37.367  5716  5736 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 12:42:37.369  5716  5736 I bt_userial_vendor: device fd = 54 open
,11-25 12:42:37.364  5737  5737 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 12:42:37.383  5716  5736 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 12:42:37.385  5716  5736 D bt_hwcfg: Chipset BCM4358A3
,11-25 12:42:37.386  5716  5736 D bt_hwcfg: Target name = [BCM4358A3]
11-25 12:42:37.386  5716  5736 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 12:42:37.780  5716  5736 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 12:42:37.780  5716  5736 D bt_hwcfg: Settlement delay -- 100 ms
11-25 12:42:37.780  5716  5736 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 12:42:37.914  5716  5736 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-25 12:42:37.915  5716  5736 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-25 12:42:37.916  5716  5736 I bt_hwcfg: vendor lib fwcfg completed
,11-25 12:42:37.916  5716  5736 I bt_vendor: firmware callback
,11-25 12:42:37.917  5716  5736 I bt_hci  : firmware_config_callback
11-25 12:42:37.925  5716  5739 I bt_btu  : btu_task pending for preload complete event
,11-25 12:42:37.925  5716  5739 I bt_btu_task: Bluetooth chip preload is complete
11-25 12:42:37.925  5716  5739 I bt_btu  : btu_task received preload complete event
,11-25 12:42:37.932  5716  5739 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 12:42:37.932  5716  5739 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 12:42:37.932  5716  5739 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-25 12:42:37.932  5716  5739 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 12:42:37.932  5716  5739 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-25 12:42:37.932  5716  5739 I         : BTE_InitTraceLevels -- TRC_A2D
,11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_PAN
,11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_SDP
,11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 12:42:37.933  5716  5739 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-25 12:42:37.934  5716  5739 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 12:42:38.015  5716  5739 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b77549
11-25 12:42:38.015  5716  5739 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b77549 
,11-25 12:42:38.033  5716  5732 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 12:42:38.034  5716  5732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 12:42:38.035  5716  5732 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-25 12:42:38.037  5716  5732 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 12:42:38.039  5716  5732 D BluetoothAdapterProperties: Scan Mode:20
,11-25 12:42:38.040  5716  5732 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 12:42:38.040  5716  5732 D bt_hci  : do_postload posting postload work item
11-25 12:42:38.040  5716  5736 I bt_hci  : event_postload
11-25 12:42:38.040  5716  5736 I bt_vendor: sco_config_cb
,11-25 12:42:38.040  5716  5736 I bt_hci  : sco_config_callback postload finished.
,11-25 12:42:38.044  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:38.047  5716  5732 D bt_bte_conf: Device ID record 1 : primary
11-25 12:42:38.047  5716  5732 D bt_bte_conf:   vendorId            = 000f
11-25 12:42:38.047  5716  5732 D bt_bte_conf:   vendorIdSource      = 0001
11-25 12:42:38.047  5716  5732 D bt_bte_conf:   product             = 1200
,11-25 12:42:38.047  5716  5732 D bt_bte_conf:   version             = 1436
11-25 12:42:38.047  5716  5732 D bt_bte_conf:   clientExecutableURL = 
,11-25 12:42:38.047  5716  5732 D bt_bte_conf:   serviceDescription  = 
11-25 12:42:38.048  5716  5732 D bt_bte_conf:   documentationURL    = 
11-25 12:42:38.048  5716  5732 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 12:42:38.048  5716  5729 D bt_stack_manager: event_start_up_stack finished
,11-25 12:42:38.049  5716  5728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 12:42:38.049  5716  5728 D BluetoothAdapterProperties: Setting state to 15
11-25 12:42:38.049  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 12:42:38.051  5716  5728 I BluetoothAdapterState: Entering BleOnState
,11-25 12:42:38.055  5716  5736 I bt_vendor: low_power_mode_cb
11-25 12:42:38.056  5716  5728 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 12:42:38.056  5716  5728 D BluetoothAdapterProperties: Setting state to 11
11-25 12:42:38.056  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 12:42:38.060  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
,11-25 12:42:38.061  5716  5716 D HeadsetService: Received start request. Starting profile...
,11-25 12:42:38.063  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:38.068  5716  5716 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 12:42:38.068  5716  5716 D HeadsetStateMachine: make
,11-25 12:42:38.075  5716  5728 I BluetoothAdapterState: Entering PendingCommandState
,11-25 12:42:38.077  5716  5716 D HeadsetStateMachine: max_hf_connections = 1
,11-25 12:42:38.077  5716  5716 I bt_bluedroid: get_profile_interface handsfree
11-25 12:42:38.077  5716  5732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 12:42:38.078  5716  5732 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-25 12:42:38.080  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
,11-25 12:42:38.081  5716  5716 D A2dpService: Received start request. Starting profile...
11-25 12:42:38.082  5716  5716 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 12:42:38.082  5716  5716 I bt_bluedroid: get_profile_interface avrcp
,11-25 12:42:38.088  5716  5716 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 12:42:38.088  5716  5716 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 12:42:38.088  5716  5716 D A2dpStateMachine: make
11-25 12:42:38.089  5716  5716 I bt_bluedroid: get_profile_interface a2dp
,11-25 12:42:38.090  5716  5732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-25 12:42:38.091  5716  5747 D A2dpStateMachine: Enter Disconnected: -2
,11-25 12:42:38.092  5716  5716 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 12:42:38.093  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:38.096  5716  5716 D HidService: Received start request. Starting profile...
11-25 12:42:38.096  5716  5716 I bt_bluedroid: get_profile_interface hidhost
11-25 12:42:38.096  5716  5716 D HidService: setHidService(): set to: null
11-25 12:42:38.096  5716  5732 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b5856d
11-25 12:42:38.096  5716  5732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 12:42:38.098  5564  5564 D BluetoothInputDevice: Proxy object connected
,11-25 12:42:38.099  5716  5716 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 12:42:38.099  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:38.099  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:38.100  5716  5716 D HealthService: Received start request. Starting profile...
11-25 12:42:38.101  5564  5564 D HidProfile: Bluetooth service connected
11-25 12:42:38.102  5716  5716 I bt_bluedroid: get_profile_interface health
11-25 12:42:38.103  5716  5716 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-25 12:42:38.104  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:38.105  5564  5564 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 12:42:38.105  5564  5564 D PanProfile: Bluetooth service connected
11-25 12:42:38.105  5716  5716 D PanService: Received start request. Starting profile...
11-25 12:42:38.105  5716  5716 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 12:42:38.105  5716  5716 I bt_bluedroid: get_profile_interface pan
11-25 12:42:38.106  5716  5732 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 12:42:38.108  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
,11-25 12:42:38.109  5564  5564 D BluetoothMap: Proxy object connected
,11-25 12:42:38.110  5564  5564 D MapProfile: Bluetooth service connected
11-25 12:42:38.110  5564  5564 D BluetoothMap: getConnectedDevices()
11-25 12:42:38.111  5716  5716 D BluetoothMapService: Received start request. Starting profile...
11-25 12:42:38.111  5716  5716 D BluetoothMapService: start()
11-25 12:42:38.113  5716  5716 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 12:42:38.114  5716  5716 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 12:42:38.114  5716  5716 D BluetoothMapAppObserver: createReceiver()
11-25 12:42:38.115  5716  5716 D BluetoothMapAppObserver: initObservers()
11-25 12:42:38.115  5716  5716 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 12:42:38.123  5716  5716 V SapService: SapBinder()
11-25 12:42:38.123  5716  5716 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
,11-25 12:42:38.124  5716  5716 D SapService: Received start request. Starting profile...
11-25 12:42:38.124  5716  5716 V SapService: start()
11-25 12:42:38.125  5716  5716 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:38.125  5716  5716 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:38.125  5716  5745 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 12:42:38.125  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 12:42:38.125  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 12:42:38.126  5716  5716 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:38.126  5716  5716 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:38.126  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:38.126  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 12:42:38.127  5716  5716 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:38.127  5716  5716 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:38.127  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:38.127  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:38.128  5716  5716 V BluetoothAdapterState: isTurningOff()=false
,11-25 12:42:38.128  5716  5716 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:38.128  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:38.129  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:38.129  5716  5716 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:38.130  5716  5716 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:38.130  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 12:42:38.130  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:38.130  5716  5716 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:38.130  5716  5716 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:38.130  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:38.130  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:38.131  5716  5716 V BluetoothAdapterState: isTurningOff()=false
,11-25 12:42:38.131  5716  5716 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:38.131  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:38.131  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:38.132  5716  5728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 12:42:38.132  5716  5728 D BluetoothAdapterProperties: ScanMode =  20
11-25 12:42:38.132  5716  5728 D BluetoothAdapterProperties: State =  11
11-25 12:42:38.132  5716  5728 D BluetoothAdapterProperties: Setting state to 12
,11-25 12:42:38.132  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 12:42:38.133   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:38.133  5716  5728 I BluetoothAdapterState: Entering OnState
,11-25 12:42:38.133  5564  5576 D BluetoothPan: onBluetoothStateChange on: true
11-25 12:42:38.133  3009  3021 D BluetoothMap: onBluetoothStateChange: up=true
11-25 12:42:38.135  5564  5564 D BluetoothMap: Bluetooth is Not enabled
11-25 12:42:38.135  5716  5732 D BluetoothAdapterProperties: Scan Mode:21
11-25 12:42:38.136  5716  5732 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 12:42:38.136  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 12:42:38.136  3009  3009 D BluetoothMap: Proxy object connected
11-25 12:42:38.136  3009  3009 D MapProfile: Bluetooth service connected
11-25 12:42:38.136  3009  3009 D BluetoothMap: getConnectedDevices()
11-25 12:42:38.136  5564  5579 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 12:42:38.137  3009  3020 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 12:42:38.138   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:38.138  3009  3009 D BluetoothInputDevice: Proxy object connected
,11-25 12:42:38.138  3009  3009 D HidProfile: Bluetooth service connected
,11-25 12:42:38.138  3657  4009 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:38.139  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 12:42:38.139  3009  3021 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 12:42:38.141  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 12:42:38.141  3009  3009 D BluetoothA2dp: Proxy object connected
,11-25 12:42:38.142   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:38.142  3009  3864 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 12:42:38.142  5716  5716 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 12:42:38.143  5716  5716 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 12:42:38.144  5564  5576 D BluetoothPbap: onBluetoothStateChange: up=true
,11-25 12:42:38.144  5716  5716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 12:42:38.146  5564  5579 D BluetoothMap: onBluetoothStateChange: up=true
11-25 12:42:38.146  5716  5716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 12:42:38.146  3009  3865 D BluetoothPan: onBluetoothStateChange on: true
11-25 12:42:38.147  5716  5716 D ObexServerSockets: Succeed to create listening sockets 
11-25 12:42:38.147  5716  5716 D ObexServerSockets0: startAccept()
11-25 12:42:38.147  5716  5716 D ObexServerSockets0: prepareForNewConnect()
11-25 12:42:38.148  3009  3864 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:38.148  3009  3009 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 12:42:38.148  3009  3009 D PanProfile: Bluetooth service connected
11-25 12:42:38.148   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 12:42:38.149   929   929 D BluetoothA2dp: Proxy object connected
11-25 12:42:38.149  5716  5716 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 12:42:38.150  5716  5716 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 12:42:38.151  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-25 12:42:38.151  5716  5716 D BluetoothMapService: onReceive
11-25 12:42:38.151  5716  5716 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 12:42:38.151  5716  5716 D BluetoothMapService: STATE_ON
11-25 12:42:38.152  5716  5754 D ObexServerSockets0: Accepting socket connection...
11-25 12:42:38.152  5716  5753 D ObexServerSockets0: Accepting socket connection...
11-25 12:42:38.154  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:38.155   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-25 12:42:38.156  5716  5757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:38.157  5564  5564 D LocalBluetoothProfileManager: Adding local A2DP profile
11-25 12:42:38.158  5716  5757 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 12:42:38.158  5716  5757 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 12:42:38.161  5564  5564 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-25 12:42:38.168  5564  5564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 12:42:38.170  5564  5564 D BluetoothA2dp: Proxy object connected
,11-25 12:42:38.172  5716  5716 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 12:42:38.172  5716  5716 D ObexServerSockets0: prepareForNewConnect()
11-25 12:42:38.174  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:38.175  5564  5564 D DockEventReceiver: finishStartingService: stopping service
,11-25 12:42:38.182  3009  3009 D BluetoothPbap: Proxy object connected
,11-25 12:42:38.182  5564  5564 D BluetoothPbap: Proxy object connected
11-25 12:42:38.182  3009  3009 D PbapServerProfile: Bluetooth service connected
,11-25 12:42:38.182  5564  5564 D PbapServerProfile: Bluetooth service connected
,11-25 12:42:38.191  5716  5761 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:38.205  5716  5765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:38.206  5716  5765 I BtOppRfcommListener: Accept thread started.
,11-25 12:42:38.235   929   929 D BluetoothHeadset: Proxy object connected
,11-25 12:42:38.235   929   929 D BluetoothHeadset: Proxy object connected
11-25 12:42:38.235  3657  3676 D BluetoothHeadset: Proxy object connected
,11-25 12:42:38.235  3009  3020 D BluetoothHeadset: Proxy object connected
11-25 12:42:38.236  3009  3009 D HeadsetProfile: Bluetooth service connected
11-25 12:42:38.236   929   929 D BluetoothHeadset: Proxy object connected
11-25 12:42:38.238   929   946 D BluetoothHeadset: Proxy object connected
,11-25 12:42:38.239  3657  3670 D BluetoothHeadset: Proxy object connected
,11-25 12:42:38.242   929   946 D BluetoothHeadset: Proxy object connected
,11-25 12:42:38.248  3009  3865 D BluetoothHeadset: Proxy object connected
,11-25 12:42:38.248  3009  3009 D HeadsetProfile: Bluetooth service connected
,11-25 12:42:38.264  5564  5576 D BluetoothHeadset: Proxy object connected
,11-25 12:42:38.265  5564  5564 D HeadsetProfile: Bluetooth service connected
,11-25 12:42:39.862   929  2842 D ConnectivityService: handlePromptUnvalidated 101
,11-25 12:42:40.251  3541  3725 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-25 12:42:40.253  3541  3725 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-25 12:42:40.282  3453  3453 I ConfigService: onCreate
,11-25 12:42:42.090  5716  5728 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 12:42:42.091  5716  5728 D BluetoothAdapterProperties: Setting state to 13
,11-25 12:42:42.091  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-25 12:42:42.092  5716  5728 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 12:42:42.094  5716  5728 I BluetoothAdapterState: Entering PendingCommandState
,11-25 12:42:42.102  5716  5716 D BluetoothMapService: onReceive
11-25 12:42:42.102  5716  5716 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 12:42:42.102  5716  5716 D BluetoothMapService: STATE_TURNING_OFF
11-25 12:42:42.103  5716  5716 D BluetoothMapService: MAP Service closeService in
11-25 12:42:42.103  5716  5716 D BluetoothMapMasInstance0: MAP Service shutdown
11-25 12:42:42.103  5716  5716 D ObexServerSockets0: shutdown(block = true)
11-25 12:42:42.104  5716  5716 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 12:42:42.104  5716  5753 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-25 12:42:42.104  5716  5716 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 12:42:42.104  5716  5741 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-25 12:42:42.104  5716  5754 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-25 12:42:42.107  5716  5732 D BluetoothAdapterProperties: Scan Mode:20
11-25 12:42:42.107  5716  5728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 12:42:42.108  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:42.108  5506  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 12:42:42.109  5506  5506 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 12:42:42.110  5506  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 12:42:42.113  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:42.114  5716  5716 I BtOppRfcommListener: stopping Accept Thread
,11-25 12:42:42.114  5716  5765 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 12:42:42.116  5716  5765 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 12:42:42.116  5564  5564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 12:42:42.121  5716  5716 D HeadsetService: Received stop request...Stopping profile...
,11-25 12:42:42.124   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:42.125  5564  5752 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:42.125   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:42.125  5716  5716 D A2dpService: Received stop request...Stopping profile...
11-25 12:42:42.126  3657  3676 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:42.127  5716  5747 D A2dpStateMachine: Exit Disconnected: -1
,11-25 12:42:42.127  3009  3865 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:42.127   929   929 D BluetoothHeadset: Proxy object disconnected
11-25 12:42:42.128  3009  3009 D HeadsetProfile: Bluetooth service disconnected
11-25 12:42:42.129  5564  5564 D DockEventReceiver: finishStartingService: stopping service
11-25 12:42:42.130  5564  5564 D HeadsetProfile: Bluetooth service disconnected
,11-25 12:42:42.135  3009  3009 D BluetoothA2dp: Proxy object disconnected
,11-25 12:42:42.135   929   929 D BluetoothA2dp: Proxy object disconnected
11-25 12:42:42.136  5564  5564 D BluetoothA2dp: Proxy object disconnected
,11-25 12:42:42.136  5716  5716 D HidService: Received stop request...Stopping profile...
11-25 12:42:42.136  5716  5716 D HidService: Stopping Bluetooth HidService
,11-25 12:42:42.138  3009  3009 D BluetoothInputDevice: Proxy object disconnected
11-25 12:42:42.138  5564  5564 D BluetoothInputDevice: Proxy object disconnected
11-25 12:42:42.138  3009  3009 D HidProfile: Bluetooth service disconnected
11-25 12:42:42.138  5564  5564 D HidProfile: Bluetooth service disconnected
,11-25 12:42:42.139  5716  5716 D HealthService: Received stop request...Stopping profile...
11-25 12:42:42.143  5716  5716 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:42.143  5716  5716 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:42.143  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.143  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:42.144  5716  5716 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 12:42:42.144  5716  5716 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 12:42:42.145  5716  5739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:42.145  5716  5739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:42.145  5716  5739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 12:42:42.145  5716  5716 D PanService: Received stop request...Stopping profile...
11-25 12:42:42.146  5716  5732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 12:42:42.146  5716  5732 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 12:42:42.146  3009  3009 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 12:42:42.146  3009  3009 D PanProfile: Bluetooth service disconnected
11-25 12:42:42.147  5716  5716 D BluetoothMapService: Received stop request...Stopping profile...
11-25 12:42:42.147  5716  5716 D BluetoothMapService: stop()
11-25 12:42:42.147  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:42.148  5716  5716 D BluetoothMapAppObserver: deinitObservers()
11-25 12:42:42.148  5716  5716 D BluetoothMapAppObserver: removeReceiver()
11-25 12:42:42.148  5564  5564 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 12:42:42.149  5564  5564 D PanProfile: Bluetooth service disconnected
,11-25 12:42:42.150  3009  3009 D BluetoothMap: Proxy object disconnected
,11-25 12:42:42.151  3009  3009 D MapProfile: Bluetooth service disconnected
,11-25 12:42:42.151  5716  5716 D SapService: Received stop request...Stopping profile...
,11-25 12:42:42.151  5716  5716 V SapService: stop()
11-25 12:42:42.152  5716  5716 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:42.152  5716  5716 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:42.153  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.153  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:42.153  5564  5564 D BluetoothMap: Proxy object disconnected
,11-25 12:42:42.153  5564  5564 D MapProfile: Bluetooth service disconnected
11-25 12:42:42.155  5716  5739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:42.155  5716  5739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:42.155  5716  5716 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:42.155  5716  5716 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:42.156  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.156  5716  5739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 12:42:42.156  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:42.156  5716  5739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 12:42:42.156  5716  5739 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-25 12:42:42.156  5716  5739 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 12:42:42.156  5716  5716 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 12:42:42.156  5716  5716 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 12:42:42.156  5716  5716 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:42.156  5716  5716 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:42.156  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.156  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:42.157  5716  5716 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 12:42:42.155  5716  5732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-25 12:42:42.157  5716  5732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 12:42:42.157  5716  5732 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 12:42:42.157  5716  5716 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-25 12:42:42.159  3009  3009 D BluetoothPbap: Proxy object disconnected
,11-25 12:42:42.159  3009  3009 D PbapServerProfile: Bluetooth service disconnected
11-25 12:42:42.160  5716  5716 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:42.160  5716  5716 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:42.160  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.160  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:42.160  5716  5716 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 12:42:42.160  5716  5716 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 12:42:42.162  5716  5716 D BluetoothMapService: MAP Service closeService in
,11-25 12:42:42.162  5716  5716 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:42.162  5716  5716 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:42.162  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.162  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:42.162  5716  5716 D BluetoothMapService: cleanup()
11-25 12:42:42.162  5716  5716 D BluetoothMapService: MAP Service closeService in
11-25 12:42:42.162  5716  5716 V BluetoothAdapterState: isTurningOff()=true
11-25 12:42:42.162  5716  5716 V BluetoothAdapterState: isTurningOn()=false
,11-25 12:42:42.163  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.163  5716  5716 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:42.163  5564  5564 D BluetoothPbap: Proxy object disconnected
11-25 12:42:42.163  5564  5564 D PbapServerProfile: Bluetooth service disconnected
11-25 12:42:42.163  5716  5728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-25 12:42:42.163  5716  5728 D BluetoothAdapterProperties: Setting state to 15
11-25 12:42:42.163  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-25 12:42:42.164  5564  5579 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 12:42:42.164  5716  5728 I BluetoothAdapterState: Entering BleOnState
11-25 12:42:42.164   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:42.164  5564  5576 D BluetoothPan: onBluetoothStateChange on: false
11-25 12:42:42.165  3009  3865 D BluetoothMap: onBluetoothStateChange: up=false
11-25 12:42:42.166  5564  5752 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 12:42:42.166  3009  3021 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-25 12:42:42.167  5564  5579 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:42.167   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:42.167  3657  3670 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:42.168  3009  3864 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 12:42:42.168   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:42.168  3009  3020 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 12:42:42.169  5564  5576 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 12:42:42.170  5564  5752 D BluetoothMap: onBluetoothStateChange: up=false
11-25 12:42:42.170  3009  3865 D BluetoothPan: onBluetoothStateChange on: false
11-25 12:42:42.171  3009  3021 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 12:42:42.171   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 12:42:42.171  5716  5728 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 12:42:42.172  5716  5728 D BluetoothAdapterProperties: Setting state to 16
11-25 12:42:42.172  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 12:42:42.174  5716  5728 D BluetoothAdapterProperties: onBleDisable
11-25 12:42:42.175  5716  5729 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 12:42:42.175  5716  5728 I BluetoothAdapterState: Entering PendingCommandState
11-25 12:42:42.176  5716  5732 D BluetoothAdapterProperties: Scan Mode:20
11-25 12:42:42.176  5564  5564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 12:42:42.177  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:42.178  5716  5739 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 12:42:42.178  5716  5739 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 12:42:42.178  5506  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 12:42:42.182  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:42.184  5564  5564 D DockEventReceiver: finishStartingService: stopping service
,11-25 12:42:42.390  5716  5732 I bt_hci  : shut_down
,11-25 12:42:42.401  5716  5736 D bt_hwcfg: hw_epilog_process
,11-25 12:42:42.401  5716  5736 I bt_vendor: low_power_mode_cb
,11-25 12:42:42.404  5716  5736 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 12:42:42.404  5716  5736 I bt_vendor: epilog_cb
11-25 12:42:42.404  5716  5736 I bt_hci  : epilog_finished_callback
,11-25 12:42:42.410  5716  5732 I bt_hci_h4: hal_close
,11-25 12:42:42.411  5716  5732 I bt_userial_vendor: device fd = 54 close
,11-25 12:42:42.535  5716  5729 D bt_stack_manager: event_shut_down_stack finished.
,11-25 12:42:42.536  5716  5728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 12:42:42.538  5716  5728 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 12:42:42.539  5716  5716 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 12:42:42.539  5716  5716 D BtGatt.GattService: Received stop request...Stopping profile...
11-25 12:42:42.540  5716  5716 D BtGatt.GattService: stop()
11-25 12:42:42.540  5716  5716 D BtGatt.AdvertiseManager: advertise clients cleared
,11-25 12:42:42.542  5716  5716 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:42.543  5716  5716 V BluetoothAdapterState: isTurningOn()=false
,11-25 12:42:42.543  5716  5716 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:42.543  5716  5716 V BluetoothAdapterState: isBleTurningOff()=true
11-25 12:42:42.543  5716  5728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-25 12:42:42.543  5716  5728 D BluetoothAdapterProperties: Setting state to 10
,11-25 12:42:42.543  5716  5728 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 12:42:42.544  5716  5728 I BluetoothAdapterState: Entering OffState
,11-25 12:42:42.547   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 12:42:42.555  5716  5716 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 12:42:42.555  5716  5716 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 12:42:42.555  5716  5716 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 12:42:42.557  5716  5729 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 12:42:42.562  5716  5716 I art     : System.exit called, status: 0
,11-25 12:42:42.562  5716  5716 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 12:42:42.582   929  3759 I ActivityManager: Process com.android.bluetooth (pid 5716) has died
,11-25 12:42:44.284   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:45.285   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:45.315  3453  3453 I ConfigService: onDestroy
,11-25 12:42:46.286   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:47.087  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:47.088  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 12:42:47.093  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:47.095  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e49069d removed from the list
11-25 12:42:47.095  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:47.098  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 12:42:47.098  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2a20e0 added. We now have 4 listener(s)
11-25 12:42:47.098  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:42:47.100  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:47.101  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2a20e0 removed from the list
11-25 12:42:47.101  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:42:47.103  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 12:42:47.103  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1346f99 added. We now have 4 listener(s)
11-25 12:42:47.103  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:42:47.287   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:48.288   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:42:49.289   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 12:42:52.113  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:42:52.146   929   946 I ActivityManager: Start proc 5774:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 12:42:52.231  5774  5774 D AdapterServiceConfig: Adding HeadsetService
,11-25 12:42:52.231  5774  5774 D AdapterServiceConfig: Adding A2dpService
11-25 12:42:52.232  5774  5774 D AdapterServiceConfig: Adding HidService
11-25 12:42:52.232  5774  5774 D AdapterServiceConfig: Adding HealthService
11-25 12:42:52.232  5774  5774 D AdapterServiceConfig: Adding PanService
11-25 12:42:52.232  5774  5774 D AdapterServiceConfig: Adding GattService
11-25 12:42:52.232  5774  5774 D AdapterServiceConfig: Adding BluetoothMapService
,11-25 12:42:52.232  5774  5774 D AdapterServiceConfig: Adding SapService
,11-25 12:42:52.242   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91c4d31:true
,11-25 12:42:52.243  5774  5774 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 12:42:52.246  5774  5774 I bt_bluedroid: init
,11-25 12:42:52.247  5774  5786 I BluetoothAdapterState: Entering OffState
,11-25 12:42:52.248  5774  5787 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-25 12:42:52.248  5774  5787 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-25 12:42:52.248  5774  5787 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 12:42:52.249  5774  5787 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 12:42:52.250  5774  5774 I bt_bluedroid: get_profile_interface socket
,11-25 12:42:52.251  5774  5774 I bt_bluedroid: get_profile_interface sdp
,11-25 12:42:52.252  5774  5790 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 12:42:52.253  5774  5790 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 12:42:52.257  5774  5785 I bt_bluedroid: config_hci_snoop_log
,11-25 12:42:52.258   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 12:42:52.262  5774  5786 D BluetoothAdapterState: Current state: OFF, message: 0
11-25 12:42:52.262  5774  5786 D BluetoothAdapterProperties: Setting state to 14
11-25 12:42:52.262  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 12:42:52.264  5774  5786 D BluetoothBondStateMachine: make
,11-25 12:42:52.266  5774  5791 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 12:42:52.269  5774  5786 I BluetoothAdapterState: Entering PendingCommandState
,11-25 12:42:52.270  5774  5774 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-25 12:42:52.272  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:52.273  5774  5774 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 12:42:52.274  5774  5774 D BtGatt.GattService: Received start request. Starting profile...
11-25 12:42:52.274  5774  5774 D BtGatt.GattService: start()
11-25 12:42:52.274  5774  5774 I bt_bluedroid: get_profile_interface gatt
11-25 12:42:52.275  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:52.275  5774  5774 D BtGatt.AdvertiseManager: advertise manager created
,11-25 12:42:52.280  5774  5774 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:52.281  5774  5774 V BluetoothAdapterState: isTurningOn()=false
11-25 12:42:52.281  5774  5774 V BluetoothAdapterState: isBleTurningOn()=true
,11-25 12:42:52.281  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:52.281  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 12:42:52.282  5774  5786 I bt_bluedroid: bt_bluedroid
,11-25 12:42:52.282  5774  5787 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 12:42:52.283  5774  5787 I bt_hci  : start_up
,11-25 12:42:52.287  5774  5787 I bt_vendor: alloc value 0xf3bf9871
11-25 12:42:52.287  5774  5787 I bt_vendor: init
,11-25 12:42:52.287  5774  5787 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 12:42:52.288  5774  5787 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 12:42:52.396  5774  5787 D bt_hci  : start_up starting async portion
11-25 12:42:52.397  5774  5794 I bt_hci  : event_finish_startup
11-25 12:42:52.397  5774  5794 I bt_hci_h4: hal_open
11-25 12:42:52.397  5774  5794 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 12:42:52.394  5795  5795 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 12:42:52.400  5774  5794 I bt_userial_vendor: device fd = 54 open
,11-25 12:42:52.414  5774  5794 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 12:42:52.416  5774  5794 D bt_hwcfg: Chipset BCM4358A3
,11-25 12:42:52.416  5774  5794 D bt_hwcfg: Target name = [BCM4358A3]
11-25 12:42:52.417  5774  5794 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 12:42:52.936  5774  5794 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 12:42:52.937  5774  5794 D bt_hwcfg: Settlement delay -- 100 ms
11-25 12:42:52.937  5774  5794 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 12:42:53.071  5774  5794 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-25 12:42:53.071  5774  5794 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-25 12:42:53.073  5774  5794 I bt_hwcfg: vendor lib fwcfg completed
11-25 12:42:53.073  5774  5794 I bt_vendor: firmware callback
11-25 12:42:53.073  5774  5794 I bt_hci  : firmware_config_callback
,11-25 12:42:53.084  5774  5797 I bt_btu  : btu_task pending for preload complete event
,11-25 12:42:53.084  5774  5797 I bt_btu_task: Bluetooth chip preload is complete
11-25 12:42:53.084  5774  5797 I bt_btu  : btu_task received preload complete event
,11-25 12:42:53.091  5774  5797 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 12:42:53.092  5774  5797 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 12:42:53.092  5774  5797 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 12:42:53.092  5774  5797 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-25 12:42:53.092  5774  5797 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 12:42:53.092  5774  5797 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 12:42:53.092  5774  5797 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 12:42:53.092  5774  5797 I         : BTE_InitTraceLevels -- TRC_BTM
,11-25 12:42:53.093  5774  5797 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 12:42:53.093  5774  5797 I         : BTE_InitTraceLevels -- TRC_PAN
,11-25 12:42:53.093  5774  5797 I         : BTE_InitTraceLevels -- TRC_SDP
11-25 12:42:53.093  5774  5797 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 12:42:53.093  5774  5797 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 12:42:53.093  5774  5797 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-25 12:42:53.093  5774  5797 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 12:42:53.189  5774  5797 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b77549
11-25 12:42:53.190  5774  5797 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b77549 
,11-25 12:42:53.210  5774  5790 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 12:42:53.213  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 12:42:53.214  5774  5790 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-25 12:42:53.216  5774  5790 D BluetoothAdapterProperties: Name is: Nexus 6P
11-25 12:42:53.218  5774  5790 D BluetoothAdapterProperties: Scan Mode:20
,11-25 12:42:53.218  5774  5790 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 12:42:53.219  5774  5790 D bt_hci  : do_postload posting postload work item
,11-25 12:42:53.219  5774  5794 I bt_hci  : event_postload
11-25 12:42:53.219  5774  5794 I bt_vendor: sco_config_cb
,11-25 12:42:53.219  5774  5794 I bt_hci  : sco_config_callback postload finished.
,11-25 12:42:53.223  5774  5790 D bt_bte_conf: Device ID record 1 : primary
,11-25 12:42:53.223  5774  5790 D bt_bte_conf:   vendorId            = 000f
11-25 12:42:53.223  5774  5790 D bt_bte_conf:   vendorIdSource      = 0001
,11-25 12:42:53.224  5774  5790 D bt_bte_conf:   product             = 1200
11-25 12:42:53.224  5774  5790 D bt_bte_conf:   version             = 1436
11-25 12:42:53.224  5774  5790 D bt_bte_conf:   clientExecutableURL = 
11-25 12:42:53.224  5774  5790 D bt_bte_conf:   serviceDescription  = 
,11-25 12:42:53.224  5774  5790 D bt_bte_conf:   documentationURL    = 
,11-25 12:42:53.224  5774  5790 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 12:42:53.224  5774  5787 D bt_stack_manager: event_start_up_stack finished
11-25 12:42:53.225  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 12:42:53.226  5774  5786 D BluetoothAdapterProperties: Setting state to 15
11-25 12:42:53.226  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-25 12:42:53.227  5774  5786 I BluetoothAdapterState: Entering BleOnState
,11-25 12:42:53.227  5774  5794 I bt_vendor: low_power_mode_cb
,11-25 12:42:53.232  5774  5786 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 12:42:53.233  5774  5786 D BluetoothAdapterProperties: Setting state to 11
11-25 12:42:53.233  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 12:42:53.245  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
,11-25 12:42:53.251  5774  5774 D HeadsetService: Received start request. Starting profile...
,11-25 12:42:53.254  5774  5774 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-25 12:42:53.255  5774  5774 D HeadsetStateMachine: make
11-25 12:42:53.258  5774  5786 I BluetoothAdapterState: Entering PendingCommandState
,11-25 12:42:53.265  5774  5774 D HeadsetStateMachine: max_hf_connections = 1
11-25 12:42:53.266  5774  5774 I bt_bluedroid: get_profile_interface handsfree
,11-25 12:42:53.266  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-25 12:42:53.269  5774  5790 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-25 12:42:53.270  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:53.271  5774  5774 D A2dpService: Received start request. Starting profile...
11-25 12:42:53.271  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:53.272  5774  5774 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 12:42:53.272  5774  5774 I bt_bluedroid: get_profile_interface avrcp
,11-25 12:42:53.281  5774  5774 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-25 12:42:53.281  5774  5774 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 12:42:53.281  5774  5774 D A2dpStateMachine: make
,11-25 12:42:53.282  5774  5774 I bt_bluedroid: get_profile_interface a2dp
,11-25 12:42:53.283  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 12:42:53.285  5774  5805 D A2dpStateMachine: Enter Disconnected: -2
,11-25 12:42:53.285  5774  5774 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 12:42:53.286  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
,11-25 12:42:53.287  5774  5774 D HidService: Received start request. Starting profile...
,11-25 12:42:53.287  5774  5774 I bt_bluedroid: get_profile_interface hidhost
11-25 12:42:53.287  5774  5774 D HidService: setHidService(): set to: null
11-25 12:42:53.287  5774  5790 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b5856d
11-25 12:42:53.287  5774  5790 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 12:42:53.288  5774  5774 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 12:42:53.288  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:53.289  5774  5774 D HealthService: Received start request. Starting profile...
11-25 12:42:53.290  5774  5774 I bt_bluedroid: get_profile_interface health
11-25 12:42:53.291  5774  5774 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 12:42:53.291  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:53.293  5774  5774 D PanService: Received start request. Starting profile...
,11-25 12:42:53.293  5774  5774 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-25 12:42:53.294  5774  5774 I bt_bluedroid: get_profile_interface pan
11-25 12:42:53.296  5774  5790 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 12:42:53.297  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:53.298  5774  5774 D BluetoothMapService: Received start request. Starting profile...
11-25 12:42:53.298  5774  5774 D BluetoothMapService: start()
,11-25 12:42:53.301  5774  5774 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-25 12:42:53.302  5774  5774 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-25 12:42:53.302  5774  5774 D BluetoothMapAppObserver: createReceiver()
11-25 12:42:53.303  5774  5774 D BluetoothMapAppObserver: initObservers()
,11-25 12:42:53.303  5774  5774 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 12:42:53.310  5774  5774 V SapService: SapBinder()
,11-25 12:42:53.310  5774  5774 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
11-25 12:42:53.311  5774  5774 D SapService: Received start request. Starting profile...
11-25 12:42:53.311  5774  5774 V SapService: start()
,11-25 12:42:53.313  5774  5774 V BluetoothAdapterState: isTurningOff()=false
,11-25 12:42:53.313  5774  5774 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:53.313  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:53.314  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 12:42:53.314  5774  5803 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 12:42:53.314  5774  5774 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:53.314  5774  5774 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:53.314  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 12:42:53.314  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:53.315  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 12:42:53.316  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:53.316  5774  5774 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:53.316  5774  5774 V BluetoothAdapterState: isTurningOn()=true
11-25 12:42:53.316  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:53.316  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 12:42:53.317  5774  5774 V BluetoothAdapterState: isTurningOff()=false
11-25 12:42:53.317  5774  5774 V BluetoothAdapterState: isTurningOn()=true
,11-25 12:42:53.317  5774  5774 V BluetoothAdapterState: isBleTurningOn()=false
11-25 12:42:53.317  5774  5774 V BluetoothAdapterState: isBleTurningOff()=false
11-25 12:42:53.317  5774  5786 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 12:42:53.317  5774  5786 D BluetoothAdapterProperties: ScanMode =  20
11-25 12:42:53.317  5774  5786 D BluetoothAdapterProperties: State =  11
11-25 12:42:53.317  5774  5786 D BluetoothAdapterProperties: Setting state to 12
11-25 12:42:53.318  5774  5786 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 12:42:53.318  5774  5786 I BluetoothAdapterState: Entering OnState
11-25 12:42:53.318  5564  5579 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 12:42:53.319  5774  5790 D BluetoothAdapterProperties: Scan Mode:21
11-25 12:42:53.319  5774  5790 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 12:42:53.320   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 12:42:53.320  5564  5576 D BluetoothPan: onBluetoothStateChange on: true
11-25 12:42:53.322  5564  5564 D BluetoothA2dp: Proxy object connected
,11-25 12:42:53.325  3009  3864 D BluetoothMap: onBluetoothStateChange: up=true
,11-25 12:42:53.329  5564  5564 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 12:42:53.329  5564  5564 D PanProfile: Bluetooth service connected
,11-25 12:42:53.329  5774  5774 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 12:42:53.330  5774  5774 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 12:42:53.330  5564  5752 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 12:42:53.331  5774  5774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 12:42:53.332  3009  3020 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 12:42:53.333  5774  5774 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:53.334  5564  5576 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:53.334   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:53.334  5774  5774 D ObexServerSockets: Succeed to create listening sockets 
11-25 12:42:53.334  5774  5774 D ObexServerSockets0: startAccept()
11-25 12:42:53.334  5774  5774 D ObexServerSockets0: prepareForNewConnect()
11-25 12:42:53.334  3657  3670 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:53.335  3009  3865 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 12:42:53.336   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:53.336  3009  3009 D BluetoothA2dp: Proxy object connected
11-25 12:42:53.336  5774  5774 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-25 12:42:53.337  3009  3020 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 12:42:53.337  5774  5774 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 12:42:53.338  5774  5811 D ObexServerSockets0: Accepting socket connection...
11-25 12:42:53.339  5774  5810 D ObexServerSockets0: Accepting socket connection...
11-25 12:42:53.339  5564  5579 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 12:42:53.339  3009  3009 D BluetoothMap: Proxy object connected
11-25 12:42:53.339  3009  3009 D MapProfile: Bluetooth service connected
11-25 12:42:53.340  3009  3009 D BluetoothMap: getConnectedDevices()
11-25 12:42:53.341  5564  5564 D BluetoothInputDevice: Proxy object connected
11-25 12:42:53.341  5564  5564 D HidProfile: Bluetooth service connected
11-25 12:42:53.341  3009  3009 D BluetoothInputDevice: Proxy object connected
11-25 12:42:53.341  3009  3009 D HidProfile: Bluetooth service connected
11-25 12:42:53.342  5564  5752 D BluetoothMap: onBluetoothStateChange: up=true
11-25 12:42:53.344  3009  3864 D BluetoothPan: onBluetoothStateChange on: true
11-25 12:42:53.345  3009  3009 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 12:42:53.345  3009  3021 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 12:42:53.345  3009  3009 D PanProfile: Bluetooth service connected
11-25 12:42:53.346   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-25 12:42:53.346   929   929 D BluetoothA2dp: Proxy object connected
,11-25 12:42:53.346  5564  5564 D BluetoothMap: Proxy object connected
11-25 12:42:53.346  5564  5564 D MapProfile: Bluetooth service connected
11-25 12:42:53.347  5774  5774 D BluetoothMapService: onReceive
11-25 12:42:53.347  5774  5774 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 12:42:53.348  5774  5774 D BluetoothMapService: STATE_ON
11-25 12:42:53.347  5564  5564 D BluetoothMap: getConnectedDevices()
11-25 12:42:53.349   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-25 12:42:53.352  5774  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:53.353  5774  5812 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-25 12:42:53.353  5774  5812 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 12:42:53.356  5564  5564 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 12:42:53.362  3453  3453 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 12:42:53.362  5564  5564 D DockEventReceiver: finishStartingService: stopping service
,11-25 12:42:53.369  3009  3009 D BluetoothPbap: Proxy object connected
11-25 12:42:53.369  3009  3009 D PbapServerProfile: Bluetooth service connected
,11-25 12:42:53.371  5564  5564 D BluetoothPbap: Proxy object connected
11-25 12:42:53.371  5564  5564 D PbapServerProfile: Bluetooth service connected
,11-25 12:42:53.376  5774  5774 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 12:42:53.376  5774  5774 D ObexServerSockets0: prepareForNewConnect()
,11-25 12:42:53.378  5774  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:53.395  5774  5821 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 12:42:53.396  5774  5821 I BtOppRfcommListener: Accept thread started.
,11-25 12:42:53.423   929   929 D BluetoothHeadset: Proxy object connected
,11-25 12:42:53.423  5564  5752 D BluetoothHeadset: Proxy object connected
11-25 12:42:53.424   929   929 D BluetoothHeadset: Proxy object connected
11-25 12:42:53.424  3657  3874 D BluetoothHeadset: Proxy object connected
,11-25 12:42:53.424  3009  3020 D BluetoothHeadset: Proxy object connected
11-25 12:42:53.424  3009  3009 D HeadsetProfile: Bluetooth service connected
11-25 12:42:53.424   929   929 D BluetoothHeadset: Proxy object connected
11-25 12:42:53.425  5564  5564 D HeadsetProfile: Bluetooth service connected
,11-25 12:42:53.434  5564  5579 D BluetoothHeadset: Proxy object connected
,11-25 12:42:53.434   929   946 D BluetoothHeadset: Proxy object connected
11-25 12:42:53.435  3657  4009 D BluetoothHeadset: Proxy object connected
,11-25 12:42:53.435  5564  5564 D HeadsetProfile: Bluetooth service connected
11-25 12:42:53.437   929   946 D BluetoothHeadset: Proxy object connected
,11-25 12:42:53.446  3009  3864 D BluetoothHeadset: Proxy object connected
11-25 12:42:53.446  3009  3009 D HeadsetProfile: Bluetooth service connected
,11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 12:42:57.132  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 12:42:57.138  5506  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 12:42:57.139  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:42:57.140  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1346f99 removed from the list
,11-25 12:42:57.140  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:42:57.142  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 12:42:57.142  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6aa525e added. We now have 4 listener(s)
11-25 12:42:57.142  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:42:57.146   929  3759 D WifiService: setWifiEnabled: false pid=5506, uid=10077
,11-25 12:42:57.146   929  3759 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 12:42:57.778  3916  4357 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-25 12:43:02.157  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 12:43:02.159   929  3667 D WifiService: setWifiEnabled: true pid=5506, uid=10077
,11-25 12:43:02.159   929  3667 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 12:43:02.167   507   921 D SoftapController: Softap fwReload - Ok
,11-25 12:43:02.174   507   921 D CommandListener: Setting iface cfg
,11-25 12:43:02.175   507   921 D CommandListener: Trying to bring down wlan0
,11-25 12:43:02.177   507   921 D CommandListener: Clearing all IP addresses on wlan0
,11-25 12:43:02.182   929  2827 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 12:43:02.855   929  2827 D wifi    : set interface wlan0 flags (UP)
,11-25 12:43:02.861   929  2827 I WifiHAL : Initializing wifi
11-25 12:43:02.861   929  2827 I WifiHAL : Creating socket
,11-25 12:43:02.864   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-25 12:43:02.867   929  2827 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-25 12:43:02.867   929  2827 D wifi    : Did set static halHandle = 0x7f91716680
11-25 12:43:02.867   929  2827 D wifi    : halHandle = 0x7f91716680, mVM = 0x7fadd0d140, mCls = 0x201922
11-25 12:43:02.868   929  2827 D wifi    : array field set
11-25 12:43:02.868   929  2827 I WifiNative-HAL: interface[0] = wlan0
11-25 12:43:02.873   929  5826 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547900974720
11-25 12:43:02.873   929  5826 D wifi    : waitForHalEvents called, vm = 0x7fadd0d140, obj = 0x201922, env = 0x7fa3247c00
,11-25 12:43:02.916  5827  5827 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 12:43:02.973   929  2827 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 12:43:02.987  5827  5827 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 12:43:03.062  5827  5827 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 12:43:03.063  5827  5827 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 12:43:03.088   929  2827 D WifiConfigStore: Loading config and enabling all networks 
,11-25 12:43:03.110   929  2827 D WifiConfigStore: loaded 0 passpoint configs
,11-25 12:43:03.111   929  2827 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-25 12:43:03.112   929  2827 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-25 12:43:03.113   929  2827 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-25 12:43:03.114   929  2827 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-25 12:43:03.114   929  2827 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-25 12:43:03.115   929  2827 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 12:43:03.116   929  2827 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-25 12:43:03.116   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-25 12:43:03.116   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-25 12:43:03.116   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-25 12:43:03.116   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-25 12:43:03.117   929  2827 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-25 12:43:03.120   929  2827 D WifiNative-HAL: Setting external_sim to 1
,11-25 12:43:03.121  4901  4901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 12:43:03.121   929  2827 D wifi    : setting dfs flag to true, 0x7f95a23ce0
,11-25 12:43:03.121   929  2827 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 12:43:03.122   929  2827 D wifi    : setting scan oui 0x7f95a23ce0
11-25 12:43:03.122   929  2827 D WifiHAL : Sending mac address OUI
,11-25 12:43:03.126   929  2827 E native  : do suspend false
,11-25 12:43:03.137   929  2827 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-25 12:43:03.137   507   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 12:43:03.137   929   929 D RttService: SCAN_AVAILABLE : 3
,11-25 12:43:03.137   929  2950 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-25 12:43:03.138   507   921 D CommandListener: Setting iface cfg
,11-25 12:43:03.144   929  2825 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-25 12:43:03.144   929  2825 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 12:43:03.152   929  2825 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 12:43:03.153   929  2825 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-25 12:43:03.158   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=162362 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-25 12:43:04.290   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:05.291   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:06.179  5827  5827 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 12:43:06.183  5827  5827 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 12:43:06.227   929  2827 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 12:43:06.228   929  2827 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-25 12:43:06.228   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 12:43:06.241   929  2827 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 12:43:06.276   929  2827 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 12:43:06.280  5827  5827 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 12:43:06.292   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:06.716  5827  5827 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 12:43:06.749  5827  5827 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 12:43:06.751  5827  5827 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 12:43:06.761   929  2827 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 12:43:06.761   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 12:43:06.762   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 12:43:06.779   929  2827 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 12:43:06.791   507   921 D CommandListener: Setting iface cfg
,11-25 12:43:06.797   929  2827 D WifiStateMachine: Start Dhcp Watchdog 3
,11-25 12:43:06.803   929  5832 D DhcpClient: Receive thread started
,11-25 12:43:06.807   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:06.807   929  2827 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-25 12:43:06.807   929  2842 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-25 12:43:06.887   929  2827 E native  : do suspend false
,11-25 12:43:06.899   929  5831 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 12:43:06.913   929  5832 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-25 12:43:06.914   929  5831 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-25 12:43:06.917   929  5831 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-25 12:43:06.929   929  5832 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 12:43:06.930   929  5831 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-25 12:43:06.933   507   921 D CommandListener: Setting iface cfg
,11-25 12:43:06.938   929  2827 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 12:43:06.943   929  5831 D DhcpClient: Scheduling renewal in 86399s
,11-25 12:43:06.951   929  2827 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 12:43:06.952   929  2827 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 12:43:06.953   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-25 12:43:06.957   929  2842 D ConnectivityService: Adding iface wlan0 to network 102
,11-25 12:43:06.962   929  2827 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 12:43:07.001   929  2842 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 12:43:07.001   929  2842 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-25 12:43:07.003   929  2842 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-25 12:43:07.004   929  2842 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-25 12:43:07.006   929  2842 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-25 12:43:07.012   929  2842 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:07.016   929  2842 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-25 12:43:07.016   929  2842 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-25 12:43:07.017   929  2842 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-25 12:43:07.017   929  2842 D ConnectivityService:    accepting network in place of null
11-25 12:43:07.017   929  2827 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 12:43:07.017   929  2827 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 12:43:07.017   929  2842 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 12:43:07.026   929  5830 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166230, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 12:43:07.039   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 12:43:07.059   507   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 12:43:07.062   929  2842 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-25 12:43:07.062   929  2842 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 12:43:07.062  3620  3778 W QCNEJ   : |CORE| network available: 102
,11-25 12:43:07.063   929  2842 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-25 12:43:07.066   929   946 D Tethering: MasterInitialState.processMessage what=3
11-25 12:43:07.066  3620  3778 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 12:43:07.068  3620  3778 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 12:43:07.068  3620  3778 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 12:43:07.099  3836  3836 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-25 12:43:07.102  4934  4956 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 12:43:07.102  4934  4956 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 12:43:07.102  4934  4956 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 12:43:07.102  4934  4956 E SarControlService: no key has been found,reset the power
11-25 12:43:07.105  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 12:43:07.105  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 12:43:07.105  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-25 12:43:07.106  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-25 12:43:07.106  4959  4959 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 12:43:07.107  4934  4971 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 12:43:07.108  4934  4971 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 12:43:07.108  4934  4971 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 12:43:07.109   929  5829 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-25 12:43:07.109  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 12:43:07.109  4959  4959 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 12:43:07.114  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000f003000000000000ffffffff]
11-25 12:43:07.114  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:43:07.114  4959  4973 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-25 12:43:07.114  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 12:43:07.114  4934  4945 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 12:43:07.115  4959  4973 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@12d0729 HexData = [00000000f103000000000000ffffffff]
11-25 12:43:07.115  4959  4973 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 12:43:07.115  4959  4973 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-25 12:43:07.115  4959  4959 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-25 12:43:07.116  4934  4944 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 12:43:07.117  3568  3568 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 12:43:07.121  3568  3568 D SystemUpdateService: onCreate
,11-25 12:43:07.127  3568  3568 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 12:43:07.138  3568  5843 I SystemUpdateService: active receiver: enabled
,11-25 12:43:07.145  3568  5843 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 12:43:07.148  3568  5843 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 12:43:07.148  3568  5843 I SystemUpdateService: now status is 0 (complete)
,11-25 12:43:07.148  3568  5843 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 12:43:07.148  3568  5843 I SystemUpdateService: file has been verified
11-25 12:43:07.148  3568  5843 I SystemUpdateService: OTA package size = 21989297
,11-25 12:43:07.154  3568  5843 I SystemUpdateService: showing system update notification
,11-25 12:43:07.159   929  5829 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 11:43:07 GMT], X-Android-Received-Millis=[1480074187158], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480074187135]}
11-25 12:43:07.159   929  2842 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 12:43:07.159   929  2842 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-25 12:43:07.159   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:07.160   929  2842 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 12:43:07.163   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-25 12:43:07.166  3568  3568 D SystemUpdateService: onDestroy
,11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 12:43:07.172  5506  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 12:43:07.174  5506  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 12:43:07.174  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.175  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6aa525e removed from the list
11-25 12:43:07.175  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 12:43:07.178  5506  5553 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-25 12:43:07.178  5506  5553 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-25 12:43:07.180  5506  5553 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b8b2012 Bundle[{}]
,11-25 12:43:07.181  5506  5553 I io.jxcore.node.LifeCycleMonitor: start: OK
11-25 12:43:07.181  5506  5553 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-25 12:43:07.182  5506  5553 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-25 12:43:07.182  5506  5553 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-25 12:43:07.183  5506  5553 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-25 12:43:07.183  5506  5553 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-25 12:43:07.189  5506  5553 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-25 12:43:07.190  5506  5553 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-25 12:43:07.190  5506  5553 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-25 12:43:07.192  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 12:43:07.193  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e51e63f added. We now have 3 listener(s)
11-25 12:43:07.194  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.194  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.194  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 12:43:07.194  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.194  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06b0c added. We now have 4 listener(s)
11-25 12:43:07.194  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:43:07.195  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 12:43:07.198  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 12:43:07.198  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d36c55 added. We now have 4 listener(s)
11-25 12:43:07.199  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 12:43:07.199  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.200  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 12:43:07.200  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.200  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c5366a added. We now have 5 listener(s)
11-25 12:43:07.200  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:43:07.201  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:43:07.201  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:43:07.201  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:43:07.201  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.201  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 12:43:07.201  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.202  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e51e63f removed from the list
11-25 12:43:07.202  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.202  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06b0c removed from the list
11-25 12:43:07.202  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:43:07.202  3453  5846 I VacuumService: Vacuum at: now=1480074187202 tag=VacuumService
11-25 12:43:07.202  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.202  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.203  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.204  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.204  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.204  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.204  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.204  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.204  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06b0c not in the list
11-25 12:43:07.204  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.204  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.205  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.206  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.206  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.206  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.206  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.206  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.206  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c5366a removed from the list
11-25 12:43:07.206  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.206  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.206  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.206  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d36c55 removed from the list
11-25 12:43:07.207  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 12:43:07.207  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@288a75b added. We now have 3 listener(s)
,11-25 12:43:07.208  3568  3568 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 12:43:07.209  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.209  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.209  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 12:43:07.209  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.210  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f2bf8 added. We now have 4 listener(s)
11-25 12:43:07.210  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:43:07.210  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 12:43:07.212  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 12:43:07.212  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b78d1 added. We now have 4 listener(s)
11-25 12:43:07.213  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.213  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.213  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 12:43:07.213  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.213  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f84f36 added. We now have 5 listener(s)
11-25 12:43:07.213  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:43:07.214  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:43:07.214  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 12:43:07.214  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 12:43:07.214  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:43:07.214  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 12:43:07.214  3568  5283 I iu.UploadsManager: num queued entries: 0
11-25 12:43:07.215  3568  5283 I iu.UploadsManager: num updated entries: 0
11-25 12:43:07.215  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 12:43:07.216  3568  3568 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 12:43:07.218  3568  3568 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 12:43:07.220  3568  5283 I iu.SyncManager: NEXT; no task
,11-25 12:43:07.221  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 12:43:07.221  5506  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 12:43:07.221  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 12:43:07.221  5630  5630 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 12:43:07.225  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.225  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 12:43:07.226  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 12:43:07.226  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 12:43:07.226  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 12:43:07.227  5630  5630 D SprintDMHelper: simOperator: 
11-25 12:43:07.227  5630  5630 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-25 12:43:07.229  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.229  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 12:43:07.229  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 12:43:07.229  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 12:43:07.229  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 12:43:07.230  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.230  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.233  5774  5802 D BtGatt.GattService: registerClient() - UUID=452dd13e-62de-4c20-9927-ee74c051e760
11-25 12:43:07.233  5774  5790 D BtGatt.GattService: onClientRegistered() - UUID=452dd13e-62de-4c20-9927-ee74c051e760, clientIf=5
11-25 12:43:07.234  5506  5517 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 12:43:07.235  3453  5852 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-25 12:43:07.235  5774  5813 D BtGatt.GattService: start scan with filters
,11-25 12:43:07.239  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 12:43:07.239  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.239  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 12:43:07.240  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.240  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 12:43:07.240  5774  5793 D BtGatt.ScanManager: handling starting scan
11-25 12:43:07.240  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 12:43:07.240  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.240  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 12:43:07.240  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 12:43:07.240  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.240  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.240  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.240  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.241  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 12:43:07.241  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.242  5774  5793 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7197186
,11-25 12:43:07.244  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.244  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:43:07.244  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.244  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.244  5506  5553 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 12:43:07.244  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 12:43:07.244  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 12:43:07.244  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.245  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.245  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:43:07.245  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.245  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 12:43:07.249  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.249  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.249  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.249  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 12:43:07.249  5774  5790 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 12:43:07.249  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.250  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:43:07.250  5774  5793 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 12:43:07.249  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.252  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 12:43:07.252  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 12:43:07.252  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.252  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.252  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.252  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 12:43:07.252  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.255  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.256  5774  5785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 12:43:07.256  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 12:43:07.256  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.257  5774  5784 D BtGatt.GattService: stopScan() - queue size =1
11-25 12:43:07.257  5774  5790 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 12:43:07.257  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.257  5774  5793 D BtGatt.ScanManager: Starting BLE batch scan
11-25 12:43:07.258  5774  5813 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 12:43:07.258  5774  5793 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.258  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 12:43:07.259  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 12:43:07.259  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 12:43:07.261  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.263  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.263  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:43:07.263  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.263  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.263  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:43:07.264  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:43:07.264  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 12:43:07.264  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.264  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 12:43:07.264  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 12:43:07.264  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.264  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.264  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.264  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:43:07.264  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.264  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.267  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:43:07.267  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 12:43:07.267  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:43:07.267  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.267  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.267  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.267  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@288a75b removed from the list
11-25 12:43:07.267  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.267  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f2bf8 removed from the list
11-25 12:43:07.267  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:43:07.267  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.267  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.268  5774  5790 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 12:43:07.268  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.268  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.268  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.268  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.269  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.269  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.269  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.269  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.269  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.269  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.269  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28f2bf8 not in the list
,11-25 12:43:07.269  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.270  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.272  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.272  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.272  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.272  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.272  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.272  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.272  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f84f36 removed from the list
,11-25 12:43:07.273  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.273  5774  5790 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 12:43:07.273  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.273  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.273  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.273  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b78d1 removed from the list
11-25 12:43:07.274  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 12:43:07.274  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@912a6d3 added. We now have 3 listener(s)
11-25 12:43:07.275  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.275  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.275  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 12:43:07.275  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.276  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f78210 added. We now have 4 listener(s)
11-25 12:43:07.276  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 12:43:07.276  5774  5793 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 12:43:07.276  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 12:43:07.277  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 12:43:07.277  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c637109 added. We now have 4 listener(s)
,11-25 12:43:07.279  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-25 12:43:07.279  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.279  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 12:43:07.279  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.279  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8be0f0e added. We now have 5 listener(s)
11-25 12:43:07.280  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:43:07.280  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:43:07.280  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 12:43:07.280  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 12:43:07.280  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 12:43:07.280  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:43:07.280  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-25 12:43:07.281  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 12:43:07.281  3453  5847 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-25 12:43:07.283  5774  5790 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 12:43:07.283  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.283  5774  5790 E BtGatt.ContextMap: Context not found for ID 5
,11-25 12:43:07.284  3453  5847 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-25 12:43:07.285  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 12:43:07.285  5506  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-25 12:43:07.285  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 12:43:07.288  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.288  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 12:43:07.289  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 12:43:07.289  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-25 12:43:07.289  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 12:43:07.289  5774  5790 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 12:43:07.289  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.290  5774  5793 D BtGatt.ScanManager: stopping BLe Batch
11-25 12:43:07.292  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.292  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 12:43:07.292  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 12:43:07.292  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 12:43:07.292  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 12:43:07.292  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.293  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.293   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:07.294  5774  5802 D BtGatt.GattService: registerClient() - UUID=14db385a-b9f9-4a38-9de5-82b56a5523d0
,11-25 12:43:07.295  5774  5790 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 12:43:07.295  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:43:07.295  5774  5793 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 12:43:07.295  5774  5790 D BtGatt.GattService: onClientRegistered() - UUID=14db385a-b9f9-4a38-9de5-82b56a5523d0, clientIf=5
11-25 12:43:07.295  5506  5516 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 12:43:07.295  5774  5784 D BtGatt.GattService: start scan with filters
,11-25 12:43:07.298  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 12:43:07.298  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.298  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 12:43:07.298  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.298  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 12:43:07.298  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 12:43:07.298  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.298  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 12:43:07.298  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 12:43:07.298  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.299  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.299  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.299  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.300  5774  5790 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 12:43:07.300  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.300  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 12:43:07.301  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.302  5774  5793 D BtGatt.ScanManager: handling starting scan
,11-25 12:43:07.303  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.303  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:43:07.303  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.303  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.303  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:43:07.303  5506  5553 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 12:43:07.303  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.303  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:43:07.303  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:43:07.303  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:43:07.303  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.303  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.303  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:43:07.303  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.303  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.304  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@912a6d3 removed from the list
11-25 12:43:07.304  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.304  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f78210 removed from the list
,11-25 12:43:07.304  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:43:07.304  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.304  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:43:07.304  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.304  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.304  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 12:43:07.304  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.304  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:43:07.304  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.305  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.305  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.305  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.305  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.305  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.305  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.305  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.305  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.305  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:43:07.305  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.305  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f78210 not in the list
11-25 12:43:07.305  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 12:43:07.305  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.305  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 12:43:07.306  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 12:43:07.306  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.306  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.306  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.306  5506  5553 I org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 12:43:07.306  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.306  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.307  5774  5785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 12:43:07.307  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-25 12:43:07.307  5774  5790 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 12:43:07.307  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.308  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.308  5774  5793 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 12:43:07.308  5774  5784 D BtGatt.GattService: stopScan() - queue size =1
11-25 12:43:07.308  5774  5813 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.309  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.310  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 12:43:07.310  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 12:43:07.310  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 12:43:07.310  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.311  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.311  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:43:07.311  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.311  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.311  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.312  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.312  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.312  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:43:07.312  5506  5553 V org.thaliproject.p2p.btconnec,torlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8be0f0e removed from the list
11-25 12:43:07.312  5774  5790 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 12:43:07.312  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.312  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:43:07.312  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.312  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.312  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.312  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 12:43:07.312  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c637109 removed from the list
11-25 12:43:07.312  5774  5793 D BtGatt.ScanManager: Starting BLE batch scan
11-25 12:43:07.312  5774  5793 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 12:43:07.312  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.312  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 12:43:07.312  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 12:43:07.312  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.312  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.312  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.312  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:43:07.312  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 12:43:07.312  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fe1d4b added. We now have 3 listener(s)
11-25 12:43:07.312  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.313  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.313  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.314  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.314  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 12:43:07.314  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 12:43:07.314  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4218328 added. We now have 4 listener(s)
11-25 12:43:07.314  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:43:07.314  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 12:43:07.315  3453  5847 W Uploader:  no longer exists, so no auth token.
11-25 12:43:07.316  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.316  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.316  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.316  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 12:43:07.317  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b3841 added. We now have 4 listener(s)
,11-25 12:43:07.318  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.318  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.318  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 12:43:07.318  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.318  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd0f1e6 added. We now have 5 listener(s)
11-25 12:43:07.318  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:43:07.318  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:43:07.318  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 12:43:07.318  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-25 12:43:07.318  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 12:43:07.318  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-25 12:43:07.320  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 12:43:07.322  3453  5852 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 12:43:07.323  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 12:43:07.323  5506  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 12:43:07.324  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 12:43:07.325  5774  5790 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 12:43:07.325  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:43:07.327  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.327  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 12:43:07.329  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 12:43:07.329  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 12:43:07.329  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 12:43:07.331  5774  5790 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 12:43:07.331  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:43:07.332  5774  5793 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 12:43:07.333  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.333  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 12:43:07.333  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 12:43:07.333  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 12:43:07.333  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 12:43:07.333  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.335  5506  5553 D BluetoothAdapter: STATE_ON
,11-25 12:43:07.336  5774  5790 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 12:43:07.336  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.336  5774  5790 E BtGatt.ContextMap: Context not found for ID 5
,11-25 12:43:07.338  5774  5785 D BtGatt.GattService: registerClient() - UUID=c5f61b59-8e70-442d-b4ab-79d7d69dd19a
,11-25 12:43:07.338  5774  5790 D BtGatt.GattService: onClientRegistered() - UUID=c5f61b59-8e70-442d-b4ab-79d7d69dd19a, clientIf=5
11-25 12:43:07.338  5506  5516 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 12:43:07.338  5774  5813 D BtGatt.GattService: start scan with filters
11-25 12:43:07.340  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 12:43:07.340  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.340  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-25 12:43:07.340  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.341  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 12:43:07.341  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 12:43:07.341  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.341  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 12:43:07.341  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 12:43:07.341  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.341  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.341  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.341  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.342  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 12:43:07.342  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.342  5774  5790 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 12:43:07.342  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.343  5774  5793 D BtGatt.ScanManager: stopping BLe Batch
,11-25 12:43:07.344  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.344  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:43:07.344  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.344  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.344  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.346  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:43:07.346  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:43:07.346  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:43:07.346  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.346  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.346  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:43:07.346  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.346  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.346  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fe1d4b removed from the list
11-25 12:43:07.346  5774  5790 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 12:43:07.347  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.347  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.347  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4218328 removed from the list
11-25 12:43:07.347  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:43:07.347  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.347  5774  5793 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 12:43:07.347  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:43:07.347  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.347  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.347  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 12:43:07.347  5506  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 12:43:07.347  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 12:43:07.347  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.348  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.348  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.348  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.348  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.348  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.348  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.348  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.348  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.348  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.348  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4218328 not in the list
11-25 12:43:07.348  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 12:43:07.348  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 12:43:07.348  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.349  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 12:43:07.349  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 12:43:07.349  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.349  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.349  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.349  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 12:43:07.349  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.350  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.350  5774  5785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 12:43:07.350  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 12:43:07.350  5506  5553 D BluetoothAdapter: STATE_ON
11-25 12:43:07.351  5774  5790 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 12:43:07.351  5774  5813 D BtGatt.GattService: stopScan() - queue size =0
11-25 12:43:07.351  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.351  5774  5802 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.352  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 12:43:07.352  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 12:43:07.353  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 12:43:07.353  5774  5793 D BtGatt.ScanManager: handling starting scan
11-25 12:43:07.353  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.355  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.355  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:43:07.356  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.356  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.356  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.356  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.356  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.356  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd0f1e6 removed from the list
11-25 12:43:07.356  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.356  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.356  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.356  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12b3841 removed from the list
11-25 12:43:07.356  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:43:07.357  4901  5853 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-25 12:43:07.357  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 12:43:07.357  5506  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 12:43:07.357  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 12:43:07.357  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.357  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22eac3 added. We now have 3 listener(s)
11-25 12:43:07.357  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 12:43:07.357  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 12:43:07.357  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.357  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.357  5506  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 12:43:07.357  5506  5506 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 12:43:07.357  5506  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.357  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.358  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.358  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.358  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 12:43:07.358  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.358  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8378f40 added. We now have 4 listener(s)
11-25 12:43:07.358  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:43:07.359  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 12:43:07.359  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.359  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.359  5506  5506 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 12:43:07.360  5774  5790 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 12:43:07.360  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.360  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 12:43:07.360  5774  5793 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 12:43:07.360  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cdae79 added. We now have 4 listener(s)
,11-25 12:43:07.361  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-25 12:43:07.361  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 12:43:07.361  5506  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 12:43:07.361  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 12:43:07.361  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55257be added. We now have 5 listener(s)
11-25 12:43:07.361  5506  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 12:43:07.361  5506  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 12:43:07.361  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:43:07.361  5506  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 12:43:07.362  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.362  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.362  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-25 12:43:07.362  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22eac3 removed from the list
11-25 12:43:07.362  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.362  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8378f40 removed from the list
11-25 12:43:07.362  5506  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-25 12:43:07.362  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.362  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.363  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-25 12:43:07.363  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.363  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.363  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.363  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.364  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 12:43:07.364  5506  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8378f40 not in the list
11-25 12:43:07.364  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.364  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.364  5774  5790 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-25 12:43:07.364  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.364  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.364  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.365  5506  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-25 12:43:07.365  5774  5793 D BtGatt.ScanManager: Starting BLE batch scan
11-25 12:43:07.365  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 12:43:07.365  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 12:43:07.365  5774  5793 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 12:43:07.365  5506  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 12:43:07.365  5506  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55257be removed from the list
11-25 12:43:07.365  5506  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 12:43:07.365  5506  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 12:43:07.365  5506  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 12:43:07.365  5506  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cdae79 removed from the list
11-25 12:43:07.366  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 12:43:07.366  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-25 12:43:07.366  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 12:43:07.366  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 12:43:07.366  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 12:43:07.366  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 12:43:07.372  5774  5790 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 12:43:07.372  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:43:07.376  5774  5790 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 12:43:07.376  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:43:07.378  5774  5793 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 12:43:07.382  5774  5790 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 12:43:07.382  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.382  5774  5790 E BtGatt.ContextMap: Context not found for ID 5
,11-25 12:43:07.387  5774  5790 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 12:43:07.387  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.387  5774  5793 D BtGatt.ScanManager: stopping BLe Batch
,11-25 12:43:07.392  5774  5790 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 12:43:07.392  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 12:43:07.392  5774  5793 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 12:43:07.396  5774  5790 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 12:43:07.396  5774  5790 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 12:43:07.614  3453  5857 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 12:43:07.764  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 12:43:07.803  3453  5852 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 12:43:07.813  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 12:43:07.858  5506  5506 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 12:43:07.882  3453  5847 W Uploader:  no longer exists, so no auth token.
,11-25 12:43:07.895  3453  5857 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 12:43:07.981  3453  5852 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 12:43:08.070  3453  5857 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 12:43:08.294   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:09.294   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 12:43:09.518  5506  5865 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 12:43:09.518  5506  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:09.832   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:10.332  5506  5865 W !!      : call onHalfStreamCopied
,11-25 12:43:10.332  5506  5865 I testCopyDataAndClose: closing input stream
,11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 12:43:11.116  5506  5865 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 12:43:12.856   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:15.019   929  2842 D ConnectivityService: handlePromptUnvalidated 102
,11-25 12:43:15.399  5506  5866 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:15.399  5506  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:15.879   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:17.399  5506  5553 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-25 12:43:17.399  5506  5553 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:17.399  5506  5553 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-25 12:43:17.488  5506  5866 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-25 12:43:17.489  5506  5866 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:17.489  5506  5866 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-25 12:43:17.537  5506  5867 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 12:43:17.537  5506  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:18.161   929  2827 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 12:43:19.152  5506  5867 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 12:43:23.431  5506  5868 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-25 12:43:23.432  5506  5868 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 12:43:23.432  5506  5868 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-25 12:43:23.432  5506  5868 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 12:43:23.433  5506  5868 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:23.433  5506  5868 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-25 12:43:23.435  5506  5553 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-25 12:43:23.437  5506  5869 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:23.437  5506  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 12:43:23.438  5506  5869 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-25 12:43:23.438  5506  5869 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:23.438  5506  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-25 12:43:23.438  5506  5869 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-25 12:43:23.439  5506  5869 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-25 12:43:23.439  5506  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 12:43:23.442  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 12:43:23.442  5506  5553 I jxcore-log: 
11-25 12:43:23.443  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-25 12:43:23.443  5506  5553 I jxcore-log: 
,11-25 12:43:23.443  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-25 12:43:23.443  5506  5553 I jxcore-log: 
11-25 12:43:23.443  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 12:43:23.443  5506  5553 I jxcore-log: 
11-25 12:43:23.444  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG UnitTest_app: 'Total duration:  91854'
11-25 12:43:23.444  5506  5553 I jxcore-log: 
,11-25 12:43:23.446  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 12:43:23.446  5506  5553 I jxcore-log: 
,11-25 12:43:23.450  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 12:43:23.450  5506  5553 I jxcore-log: 
,11-25 12:43:23.451  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 12:43:23.451  5506  5553 I jxcore-log: 
,11-25 12:43:23.451  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 12:43:23.451  5506  5553 I jxcore-log: 
11-25 12:43:23.452  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 12:43:23.452  5506  5553 I jxcore-log: 
,11-25 12:43:23.452  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.452  5506  5553 I jxcore-log: 
,11-25 12:43:23.452  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 12:43:23.452  5506  5553 I jxcore-log: 
,11-25 12:43:23.453  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.453  5506  5553 I jxcore-log: 
,11-25 12:43:23.453  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 12:43:23.453  5506  5553 I jxcore-log: 
11-25 12:43:23.453  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 12:43:23.453  5506  5553 I jxcore-log: 
11-25 12:43:23.454  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 12:43:23.454  5506  5553 I jxcore-log: 
,11-25 12:43:23.454  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 12:43:23.454  5506  5553 I jxcore-log: 
11-25 12:43:23.454  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.454  5506  5553 I jxcore-log: 
,11-25 12:43:23.454  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 12:43:23.454  5506  5553 I jxcore-log: 
11-25 12:43:23.455  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.455  5506  5553 I jxcore-log: 
11-25 12:43:23.455  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 12:43:23.455  5506  5553 I jxcore-log: 
,11-25 12:43:23.455  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.455  5506  5553 I jxcore-log: 
11-25 12:43:23.455  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 12:43:23.455  5506  5553 I jxcore-log: 
11-25 12:43:23.456  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 12:43:23.456  5506  5553 I jxcore-log: 
,11-25 12:43:23.456  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 12:43:23.456  5506  5553 I jxcore-log: 
11-25 12:43:23.456  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 12:43:23.456  5506  5553 I jxcore-log: 
11-25 12:43:23.456  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 12:43:23.456  5506  5553 I jxcore-log: 
,11-25 12:43:23.457  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 12:43:23.457  5506  5553 I jxcore-log: 
11-25 12:43:23.457  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 12:43:23.457  5506  5553 I jxcore-log: 
,11-25 12:43:23.457  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 12:43:23.457  5506  5553 I jxcore-log: 
11-25 12:43:23.459  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 12:43:23.459  5506  5553 I jxcore-log: 
,11-25 12:43:23.459  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 12:43:23.459  5506  5553 I jxcore-log: 
11-25 12:43:23.460  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 12:43:23.460  5506  5553 I jxcore-log: 
11-25 12:43:23.460  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 12:43:23.460  5506  5553 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-25 12:43:23.460  5506  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 12:43:23.460  5506  5553 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-25 12:43:23.460  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 12:43:23.460  5506  5553 I jxcore-log: 
11-25 12:43:23.461  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.461  5506  5553 I jxcore-log: 
11-25 12:43:23.461  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 12:43:23.461  5506  5553 I jxcore-log: 
,11-25 12:43:23.461  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.461  5506  5553 I jxcore-log: 
11-25 12:43:23.461  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 12:43:23.461  5506  5553 I jxcore-log: 
11-25 12:43:23.461  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 12:43:23.461  5506  5553 I jxcore-log: 
11-25 12:43:23.467  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 12:43:23.467  5506  5553 I jxcore-log: 
,11-25 12:43:23.467  5506  5553 I jxcore-log: 2016-11-25 11:43:23 - WARN testUtils: 'myNameCallback not set!'
11-25 12:43:23.467  5506  5553 I jxcore-log: 
11-25 12:43:23.470  5506  5506 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-25 12:43:23.470  5506  5506 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-25 12:43:25.487  5506  5553 I jxcore-log: 2016-11-25 11:43:25 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 12:43:25.487  5506  5553 I jxcore-log: 
,11-25 12:43:25.490  5506  5553 I jxcore-log: 2016-11-25 11:43:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 12:43:25.490  5506  5553 I jxcore-log: 
,11-25 12:43:25.835  5506  5553 I jxcore-log: 2016-11-25 11:43:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 12:43:25.835  5506  5553 I jxcore-log: 
,11-25 12:43:25.847  5506  5553 I jxcore-log: 2016-11-25 11:43:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 12:43:25.847  5506  5553 I jxcore-log: 
,11-25 12:43:26.945  5506  5553 I jxcore-log: 2016-11-25 11:43:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 12:43:26.945  5506  5553 I jxcore-log: 
,11-25 12:43:27.132  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 12:43:27.132  5506  5553 I jxcore-log: 
,11-25 12:43:27.138  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 12:43:27.138  5506  5553 I jxcore-log: 
,11-25 12:43:27.143  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 12:43:27.143  5506  5553 I jxcore-log: 
,11-25 12:43:27.621  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 12:43:27.621  5506  5553 I jxcore-log: 
,11-25 12:43:27.666  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 12:43:27.666  5506  5553 I jxcore-log: 
,11-25 12:43:27.679  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 12:43:27.679  5506  5553 I jxcore-log: 
,11-25 12:43:27.683  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 12:43:27.683  5506  5553 I jxcore-log: 
,11-25 12:43:27.952  5506  5553 I jxcore-log: 2016-11-25 11:43:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 12:43:27.952  5506  5553 I jxcore-log: 
,11-25 12:43:28.078  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 12:43:28.078  5506  5553 I jxcore-log: 
,11-25 12:43:28.457  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 12:43:28.457  5506  5553 I jxcore-log: 
,11-25 12:43:28.466  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 12:43:28.466  5506  5553 I jxcore-log: 
,11-25 12:43:28.470  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 12:43:28.470  5506  5553 I jxcore-log: 
,11-25 12:43:28.475  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 12:43:28.475  5506  5553 I jxcore-log: 
,11-25 12:43:28.481  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 12:43:28.481  5506  5553 I jxcore-log: 
,11-25 12:43:28.508  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 12:43:28.508  5506  5553 I jxcore-log: 
,11-25 12:43:28.543  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 12:43:28.543  5506  5553 I jxcore-log: 
,11-25 12:43:28.550  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 12:43:28.550  5506  5553 I jxcore-log: 
,11-25 12:43:28.557  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 12:43:28.557  5506  5553 I jxcore-log: 
,11-25 12:43:28.572  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 12:43:28.572  5506  5553 I jxcore-log: 
,11-25 12:43:28.588  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 12:43:28.588  5506  5553 I jxcore-log: 
,11-25 12:43:28.594  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 12:43:28.594  5506  5553 I jxcore-log: 
,11-25 12:43:28.599  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 12:43:28.599  5506  5553 I jxcore-log: 
,11-25 12:43:28.613  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 12:43:28.613  5506  5553 I jxcore-log: 
,11-25 12:43:28.630  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 12:43:28.630  5506  5553 I jxcore-log: 
,11-25 12:43:28.645  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 12:43:28.645  5506  5553 I jxcore-log: 
,11-25 12:43:28.655  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 12:43:28.655  5506  5553 I jxcore-log: 
,11-25 12:43:28.668  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 12:43:28.668  5506  5553 I jxcore-log: 
,11-25 12:43:28.678  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 12:43:28.678  5506  5553 I jxcore-log: 
,11-25 12:43:28.691  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 12:43:28.691  5506  5553 I jxcore-log: 
,11-25 12:43:28.701  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 12:43:28.701  5506  5553 I jxcore-log: 
,11-25 12:43:28.708  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 12:43:28.708  5506  5553 I jxcore-log: 
,11-25 12:43:28.730  5506  5553 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 12:43:28.731  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 12:43:28.731  5506  5553 I jxcore-log: 
,11-25 12:43:28.764  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 12:43:28.764  5506  5553 I jxcore-log: 
,11-25 12:43:28.954  5506  5553 I jxcore-log: 2016-11-25 11:43:28 - DEBUG CoordinatedClient: 'connected to the test server'
11-25 12:43:28.954  5506  5553 I jxcore-log: 
,11-25 12:43:29.296   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:30.297   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:31.298   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:32.299   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:33.300   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:43:34.301   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 12:43:43.085   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:46.122   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:43:47.003   929  2827 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 12:43:59.302   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 12:43:59.302   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 12:44:01.259   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:07.308   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:09.303   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:10.305   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:11.307   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:12.308   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:13.309   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:14.310   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 12:44:19.312   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:19.416   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:20.314   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:21.315   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:22.317   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:22.446   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:23.318   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:24.320   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 12:44:27.009   929  2827 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 12:44:34.321   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:34.560   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:35.322   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:36.324   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:37.325   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:37.587   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:38.327   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:39.327   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 12:44:47.010   929  2827 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 12:44:49.701   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:51.735  5506  5553 I jxcore-log: TAP version 13
11-25 12:44:51.735  5506  5553 I jxcore-log: 
,11-25 12:44:51.783  5506  5553 I jxcore-log: # setup
11-25 12:44:51.783  5506  5553 I jxcore-log: 
,11-25 12:44:53.062  5506  5553 I jxcore-log: # calling createNativeListener directly rejects
11-25 12:44:53.062  5506  5553 I jxcore-log: 
,11-25 12:44:53.089  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:53.089  5506  5553 I jxcore-log: 
,11-25 12:44:53.093  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'listening 37899'
11-25 12:44:53.093  5506  5553 I jxcore-log: 
,11-25 12:44:53.100  5506  5553 I jxcore-log: ok 1 Should throw
11-25 12:44:53.100  5506  5553 I jxcore-log: 
,11-25 12:44:53.110  5506  5553 I jxcore-log: # teardown
11-25 12:44:53.110  5506  5553 I jxcore-log: 
,11-25 12:44:53.543  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:53.543  5506  5553 I jxcore-log: 
,11-25 12:44:53.552  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:53.552  5506  5553 I jxcore-log: 
,11-25 12:44:53.555  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:53.555  5506  5553 I jxcore-log: 
,11-25 12:44:53.576  5506  5553 I jxcore-log: # setup
11-25 12:44:53.576  5506  5553 I jxcore-log: 
,11-25 12:44:53.680  5506  5553 I jxcore-log: # emits incomingConnectionState
11-25 12:44:53.680  5506  5553 I jxcore-log: 
,11-25 12:44:53.754  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:53.754  5506  5553 I jxcore-log: 
,11-25 12:44:53.758  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'listening 41613'
11-25 12:44:53.758  5506  5553 I jxcore-log: 
,11-25 12:44:53.767  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:53.767  5506  5553 I jxcore-log: 
,11-25 12:44:53.770  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:53.770  5506  5553 I jxcore-log: 
,11-25 12:44:53.784  5506  5553 I jxcore-log: ok 2 initial connection state should be CONNECTED
11-25 12:44:53.784  5506  5553 I jxcore-log: 
,11-25 12:44:53.806  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:53.806  5506  5553 I jxcore-log: 
,11-25 12:44:53.807  5506  5553 I jxcore-log: ok 3 final connection state should be DISCONNECTED
11-25 12:44:53.807  5506  5553 I jxcore-log: 
,11-25 12:44:53.815  5506  5553 I jxcore-log: # teardown
11-25 12:44:53.815  5506  5553 I jxcore-log: 
,11-25 12:44:53.831  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:53.831  5506  5553 I jxcore-log: 
,11-25 12:44:53.833  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:53.833  5506  5553 I jxcore-log: 
,11-25 12:44:53.835  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:53.835  5506  5553 I jxcore-log: 
,11-25 12:44:53.841  5506  5553 I jxcore-log: # setup
11-25 12:44:53.841  5506  5553 I jxcore-log: 
,11-25 12:44:53.866  5506  5553 I jxcore-log: # emits routerPortConnectionFailed
11-25 12:44:53.866  5506  5553 I jxcore-log: 
,11-25 12:44:53.908  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:53.908  5506  5553 I jxcore-log: 
,11-25 12:44:53.911  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:53.911  5506  5553 I jxcore-log: 
,11-25 12:44:53.914  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'listening 46763'
11-25 12:44:53.914  5506  5553 I jxcore-log: 
,11-25 12:44:53.921  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:53.921  5506  5553 I jxcore-log: 
,11-25 12:44:53.922  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:53.922  5506  5553 I jxcore-log: 
,11-25 12:44:53.947  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:53.947  5506  5553 I jxcore-log: 
,11-25 12:44:53.953  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
11-25 12:44:53.953  5506  5553 I jxcore-log: 
,11-25 12:44:53.954  5506  5553 I jxcore-log: ok 4 tried to connect to right port
11-25 12:44:53.954  5506  5553 I jxcore-log: 
11-25 12:44:53.955  5506  5553 I jxcore-log: ok 5 failed due to refused connection
11-25 12:44:53.955  5506  5553 I jxcore-log: 
11-25 12:44:53.955  5506  5553 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
11-25 12:44:53.955  5506  5553 I jxcore-log: 
,11-25 12:44:53.959  5506  5553 I jxcore-log: # teardown
11-25 12:44:53.959  5506  5553 I jxcore-log: 
,11-25 12:44:53.961  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:53.961  5506  5553 I jxcore-log: 
,11-25 12:44:53.962  5506  5553 I jxcore-log: 2016-11-25 11:44:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:53.962  5506  5553 I jxcore-log: 
,11-25 12:44:54.010  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.010  5506  5553 I jxcore-log: 
11-25 12:44:54.011  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:54.011  5506  5553 I jxcore-log: 
,11-25 12:44:54.013  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.013  5506  5553 I jxcore-log: 
,11-25 12:44:54.018  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.018  5506  5553 I jxcore-log: 
,11-25 12:44:54.028  5506  5553 I jxcore-log: # setup
11-25 12:44:54.028  5506  5553 I jxcore-log: 
,11-25 12:44:54.087  5506  5553 I jxcore-log: # native server connections all up
11-25 12:44:54.087  5506  5553 I jxcore-log: 
,11-25 12:44:54.140  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:54.140  5506  5553 I jxcore-log: 
,11-25 12:44:54.144  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'listening 40451'
11-25 12:44:54.144  5506  5553 I jxcore-log: 
,11-25 12:44:54.152  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:54.152  5506  5553 I jxcore-log: 
,11-25 12:44:54.154  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:54.154  5506  5553 I jxcore-log: 
,11-25 12:44:54.181  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:54.181  5506  5553 I jxcore-log: 
,11-25 12:44:54.186  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
11-25 12:44:54.186  5506  5553 I jxcore-log: 
,11-25 12:44:54.207  5506  5553 I jxcore-log: ok 7 Send/recvd #1 should be equal length
11-25 12:44:54.207  5506  5553 I jxcore-log: 
,11-25 12:44:54.208  5506  5553 I jxcore-log: ok 8 Send/recvd #1 should be same
11-25 12:44:54.208  5506  5553 I jxcore-log: 
,11-25 12:44:54.210  5506  5553 I jxcore-log: ok 9 Send/recvd #2 should be equal length
11-25 12:44:54.210  5506  5553 I jxcore-log: 
,11-25 12:44:54.211  5506  5553 I jxcore-log: ok 10 Send/recvd #2 should be same
11-25 12:44:54.211  5506  5553 I jxcore-log: 
,11-25 12:44:54.213  5506  5553 I jxcore-log: ok 11 Should be exactly 2 client sockets
11-25 12:44:54.213  5506  5553 I jxcore-log: 
,11-25 12:44:54.220  5506  5553 I jxcore-log: # teardown
11-25 12:44:54.220  5506  5553 I jxcore-log: 
,11-25 12:44:54.241  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.241  5506  5553 I jxcore-log: 
,11-25 12:44:54.244  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.244  5506  5553 I jxcore-log: 
,11-25 12:44:54.246  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:54.246  5506  5553 I jxcore-log: 
11-25 12:44:54.247  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:54.247  5506  5553 I jxcore-log: 
11-25 12:44:54.248  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
11-25 12:44:54.248  5506  5553 I jxcore-log: 
,11-25 12:44:54.250  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.250  5506  5553 I jxcore-log: 
,11-25 12:44:54.254  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.254  5506  5553 I jxcore-log: 
,11-25 12:44:54.264  5506  5553 I jxcore-log: # setup
11-25 12:44:54.264  5506  5553 I jxcore-log: 
,11-25 12:44:54.266  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
11-25 12:44:54.266  5506  5553 I jxcore-log: 
,11-25 12:44:54.269  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:54.269  5506  5553 I jxcore-log: 
,11-25 12:44:54.290  5506  5553 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
11-25 12:44:54.290  5506  5553 I jxcore-log: 
,11-25 12:44:54.316  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:54.316  5506  5553 I jxcore-log: 
,11-25 12:44:54.318  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'listening 37077'
11-25 12:44:54.318  5506  5553 I jxcore-log: 
,11-25 12:44:54.324  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:54.324  5506  5553 I jxcore-log: 
,11-25 12:44:54.325  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:54.325  5506  5553 I jxcore-log: 
,11-25 12:44:54.328   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:54.337  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:54.337  5506  5553 I jxcore-log: 
,11-25 12:44:54.352  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
11-25 12:44:54.352  5506  5553 I jxcore-log: 
,11-25 12:44:54.353  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:54.353  5506  5553 I jxcore-log: 
,11-25 12:44:54.364  5506  5553 I jxcore-log: ok 12 socket shouldn't close until after stream
11-25 12:44:54.364  5506  5553 I jxcore-log: 
,11-25 12:44:54.364  5506  5553 I jxcore-log: ok 13 incoming remains open
11-25 12:44:54.364  5506  5553 I jxcore-log: 
,11-25 12:44:54.369  5506  5553 I jxcore-log: # teardown
11-25 12:44:54.369  5506  5553 I jxcore-log: 
,11-25 12:44:54.373  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:54.373  5506  5553 I jxcore-log: 
,11-25 12:44:54.396  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.396  5506  5553 I jxcore-log: 
,11-25 12:44:54.397  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.397  5506  5553 I jxcore-log: 
11-25 12:44:54.399  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:54.399  5506  5553 I jxcore-log: 
,11-25 12:44:54.399  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.399  5506  5553 I jxcore-log: 
,11-25 12:44:54.403  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.403  5506  5553 I jxcore-log: 
,11-25 12:44:54.411  5506  5553 I jxcore-log: # setup
11-25 12:44:54.411  5506  5553 I jxcore-log: 
,11-25 12:44:54.475  5506  5553 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
11-25 12:44:54.475  5506  5553 I jxcore-log: 
,11-25 12:44:54.539  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:54.539  5506  5553 I jxcore-log: 
,11-25 12:44:54.543  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'listening 41628'
11-25 12:44:54.543  5506  5553 I jxcore-log: 
,11-25 12:44:54.550  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:54.550  5506  5553 I jxcore-log: 
,11-25 12:44:54.552  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:54.552  5506  5553 I jxcore-log: 
,11-25 12:44:54.564  5506  5553 I jxcore-log: ok 14 we should not have gotten an error
11-25 12:44:54.564  5506  5553 I jxcore-log: 
,11-25 12:44:54.570  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:54.570  5506  5553 I jxcore-log: 
,11-25 12:44:54.584  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:54.584  5506  5553 I jxcore-log: 
,11-25 12:44:54.586  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.586  5506  5553 I jxcore-log: 
,11-25 12:44:54.593  5506  5553 I jxcore-log: ok 15 socket shouldn't close until after incoming
11-25 12:44:54.593  5506  5553 I jxcore-log: 
,11-25 12:44:54.594  5506  5553 I jxcore-log: ok 16 incoming is cleaned up
11-25 12:44:54.594  5506  5553 I jxcore-log: 
,11-25 12:44:54.601  5506  5553 I jxcore-log: # teardown
11-25 12:44:54.601  5506  5553 I jxcore-log: 
,11-25 12:44:54.605  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:54.605  5506  5553 I jxcore-log: 
,11-25 12:44:54.619  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.619  5506  5553 I jxcore-log: 
,11-25 12:44:54.622  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.622  5506  5553 I jxcore-log: 
,11-25 12:44:54.623  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:54.623  5506  5553 I jxcore-log: 
,11-25 12:44:54.629  5506  5553 I jxcore-log: # setup
11-25 12:44:54.629  5506  5553 I jxcore-log: 
,11-25 12:44:54.674  5506  5553 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
11-25 12:44:54.674  5506  5553 I jxcore-log: 
,11-25 12:44:54.722  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:54.722  5506  5553 I jxcore-log: 
,11-25 12:44:54.726  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'listening 45840'
11-25 12:44:54.726  5506  5553 I jxcore-log: 
,11-25 12:44:54.736  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:54.736  5506  5553 I jxcore-log: 
,11-25 12:44:54.737  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:54.737  5506  5553 I jxcore-log: 
,11-25 12:44:54.754  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:54.754  5506  5553 I jxcore-log: 
,11-25 12:44:54.771  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
11-25 12:44:54.771  5506  5553 I jxcore-log: 
,11-25 12:44:54.772  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:54.772  5506  5553 I jxcore-log: 
,11-25 12:44:54.775  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:54.775  5506  5553 I jxcore-log: 
,11-25 12:44:54.782  5506  5553 I jxcore-log: ok 17 stream was closed
11-25 12:44:54.782  5506  5553 I jxcore-log: 
,11-25 12:44:54.782  5506  5553 I jxcore-log: ok 18 incoming should survive
11-25 12:44:54.782  5506  5553 I jxcore-log: 
11-25 12:44:54.783  5506  5553 I jxcore-log: ok 19 mux should have no streams
11-25 12:44:54.783  5506  5553 I jxcore-log: 
,11-25 12:44:54.789  5506  5553 I jxcore-log: # teardown
11-25 12:44:54.789  5506  5553 I jxcore-log: 
,11-25 12:44:54.842  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.842  5506  5553 I jxcore-log: 
,11-25 12:44:54.844  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:54.844  5506  5553 I jxcore-log: 
,11-25 12:44:54.847  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:54.847  5506  5553 I jxcore-log: 
,11-25 12:44:54.848  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.848  5506  5553 I jxcore-log: 
,11-25 12:44:54.861  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:54.861  5506  5553 I jxcore-log: 
,11-25 12:44:54.872  5506  5553 I jxcore-log: # setup
11-25 12:44:54.872  5506  5553 I jxcore-log: 
,11-25 12:44:54.929  5506  5553 I jxcore-log: # native server - closing the whole server cleans everything up
11-25 12:44:54.929  5506  5553 I jxcore-log: 
,11-25 12:44:54.963  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:54.963  5506  5553 I jxcore-log: 
,11-25 12:44:54.967  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'listening 45289'
11-25 12:44:54.967  5506  5553 I jxcore-log: 
,11-25 12:44:54.974  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:54.974  5506  5553 I jxcore-log: 
,11-25 12:44:54.979  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:54.979  5506  5553 I jxcore-log: 
,11-25 12:44:54.990  5506  5553 I jxcore-log: ok 20 we should not have gotten an error
11-25 12:44:54.990  5506  5553 I jxcore-log: 
,11-25 12:44:54.997  5506  5553 I jxcore-log: 2016-11-25 11:44:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:54.997  5506  5553 I jxcore-log: 
,11-25 12:44:55.008  5506  5553 I jxcore-log: ok 21 Buffers are identical
11-25 12:44:55.008  5506  5553 I jxcore-log: 
,11-25 12:44:55.009  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:55.009  5506  5553 I jxcore-log: 
,11-25 12:44:55.010  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:55.010  5506  5553 I jxcore-log: 
,11-25 12:44:55.011  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:55.011  5506  5553 I jxcore-log: 
,11-25 12:44:55.014  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:55.014  5506  5553 I jxcore-log: 
,11-25 12:44:55.016  5506  5553 I jxcore-log: ok 22 native server is nulled out
11-25 12:44:55.016  5506  5553 I jxcore-log: 
,11-25 12:44:55.017  5506  5553 I jxcore-log: ok 23 native server should be closed
11-25 12:44:55.017  5506  5553 I jxcore-log: 
11-25 12:44:55.017  5506  5553 I jxcore-log: ok 24 incoming has been removed
11-25 12:44:55.017  5506  5553 I jxcore-log: 
,11-25 12:44:55.018  5506  5553 I jxcore-log: ok 25 Incoming should be done
11-25 12:44:55.018  5506  5553 I jxcore-log: 
,11-25 12:44:55.018  5506  5553 I jxcore-log: ok 26 The mux object should be closed
11-25 12:44:55.018  5506  5553 I jxcore-log: 
11-25 12:44:55.018  5506  5553 I jxcore-log: ok 27 The mux stream should be closed
11-25 12:44:55.018  5506  5553 I jxcore-log: 
,11-25 12:44:55.019  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:55.019  5506  5553 I jxcore-log: 
,11-25 12:44:55.034  5506  5553 I jxcore-log: # teardown
11-25 12:44:55.034  5506  5553 I jxcore-log: 
,11-25 12:44:55.036  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:55.036  5506  5553 I jxcore-log: 
,11-25 12:44:55.062  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:55.062  5506  5553 I jxcore-log: 
,11-25 12:44:55.068  5506  5553 I jxcore-log: # setup
11-25 12:44:55.068  5506  5553 I jxcore-log: 
,11-25 12:44:55.115  5506  5553 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
11-25 12:44:55.115  5506  5553 I jxcore-log: 
,11-25 12:44:55.153  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:55.153  5506  5553 I jxcore-log: 
,11-25 12:44:55.157  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'listening 45839'
11-25 12:44:55.157  5506  5553 I jxcore-log: 
,11-25 12:44:55.179  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:55.179  5506  5553 I jxcore-log: 
,11-25 12:44:55.180  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.180  5506  5553 I jxcore-log: 
11-25 12:44:55.183  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
11-25 12:44:55.183  5506  5553 I jxcore-log: 
11-25 12:44:55.183  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.183  5506  5553 I jxcore-log: 
,11-25 12:44:55.190  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
11-25 12:44:55.190  5506  5553 I jxcore-log: 
,11-25 12:44:55.190  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.190  5506  5553 I jxcore-log: 
,11-25 12:44:55.194  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
11-25 12:44:55.194  5506  5553 I jxcore-log: 
,11-25 12:44:55.195  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.195  5506  5553 I jxcore-log: 
,11-25 12:44:55.198  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
11-25 12:44:55.198  5506  5553 I jxcore-log: 
,11-25 12:44:55.199  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.199  5506  5553 I jxcore-log: 
,11-25 12:44:55.201  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
11-25 12:44:55.201  5506  5553 I jxcore-log: 
,11-25 12:44:55.202  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.202  5506  5553 I jxcore-log: 
,11-25 12:44:55.205  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
11-25 12:44:55.205  5506  5553 I jxcore-log: 
,11-25 12:44:55.206  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.206  5506  5553 I jxcore-log: 
,11-25 12:44:55.208  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
11-25 12:44:55.208  5506  5553 I jxcore-log: 
,11-25 12:44:55.209  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.209  5506  5553 I jxcore-log: 
,11-25 12:44:55.212  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
11-25 12:44:55.212  5506  5553 I jxcore-log: 
,11-25 12:44:55.212  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.212  5506  5553 I jxcore-log: 
,11-25 12:44:55.215  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
11-25 12:44:55.215  5506  5553 I jxcore-log: 
,11-25 12:44:55.216  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:55.216  5506  5553 I jxcore-log: 
,11-25 12:44:55.271  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:55.271  5506  5553 I jxcore-log: 
,11-25 12:44:55.275  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
11-25 12:44:55.275  5506  5553 I jxcore-log: 
,11-25 12:44:55.277  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
11-25 12:44:55.277  5506  5553 I jxcore-log: 
,11-25 12:44:55.279  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
11-25 12:44:55.279  5506  5553 I jxcore-log: 
,11-25 12:44:55.281  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
11-25 12:44:55.281  5506  5553 I jxcore-log: 
,11-25 12:44:55.283  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
11-25 12:44:55.283  5506  5553 I jxcore-log: 
,11-25 12:44:55.284  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
11-25 12:44:55.284  5506  5553 I jxcore-log: 
,11-25 12:44:55.285  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
11-25 12:44:55.285  5506  5553 I jxcore-log: 
,11-25 12:44:55.287  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
11-25 12:44:55.287  5506  5553 I jxcore-log: 
,11-25 12:44:55.289  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
11-25 12:44:55.289  5506  5553 I jxcore-log: 
,11-25 12:44:55.290  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
11-25 12:44:55.290  5506  5553 I jxcore-log: 
,11-25 12:44:55.291  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
11-25 12:44:55.291  5506  5553 I jxcore-log: 
,11-25 12:44:55.293  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
11-25 12:44:55.293  5506  5553 I jxcore-log: 
,11-25 12:44:55.294  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
11-25 12:44:55.294  5506  5553 I jxcore-log: 
,11-25 12:44:55.295  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
11-25 12:44:55.295  5506  5553 I jxcore-log: 
,11-25 12:44:55.296  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
11-25 12:44:55.296  5506  5553 I jxcore-log: 
,11-25 12:44:55.298  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
11-25 12:44:55.298  5506  5553 I jxcore-log: 
,11-25 12:44:55.299  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
11-25 12:44:55.299  5506  5553 I jxcore-log: 
,11-25 12:44:55.300  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
11-25 12:44:55.300  5506  5553 I jxcore-log: 
,11-25 12:44:55.301  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
11-25 12:44:55.301  5506  5553 I jxcore-log: 
,11-25 12:44:55.302  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
11-25 12:44:55.302  5506  5553 I jxcore-log: 
11-25 12:44:55.303  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
11-25 12:44:55.303  5506  5553 I jxcore-log: 
,11-25 12:44:55.305  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
11-25 12:44:55.305  5506  5553 I jxcore-log: 
,11-25 12:44:55.306  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
11-25 12:44:55.306  5506  5553 I jxcore-log: 
,11-25 12:44:55.307  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
11-25 12:44:55.307  5506  5553 I jxcore-log: 
,11-25 12:44:55.308  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
11-25 12:44:55.308  5506  5553 I jxcore-log: 
,11-25 12:44:55.309  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
11-25 12:44:55.309  5506  5553 I jxcore-log: 
,11-25 12:44:55.310  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
11-25 12:44:55.310  5506  5553 I jxcore-log: 
,11-25 12:44:55.312  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
11-25 12:44:55.312  5506  5553 I jxcore-log: 
,11-25 12:44:55.313  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
11-25 12:44:55.313  5506  5553 I jxcore-log: 
,11-25 12:44:55.314  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
11-25 12:44:55.314  5506  5553 I jxcore-log: 
,11-25 12:44:55.315  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
11-25 12:44:55.315  5506  5553 I jxcore-log: 
,11-25 12:44:55.316  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
11-25 12:44:55.316  5506  5553 I jxcore-log: 
,11-25 12:44:55.318  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
11-25 12:44:55.318  5506  5553 I jxcore-log: 
,11-25 12:44:55.323  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
11-25 12:44:55.323  5506  5553 I jxcore-log: 
,11-25 12:44:55.325  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
11-25 12:44:55.325  5506  5553 I jxcore-log: 
,11-25 12:44:55.327  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
11-25 12:44:55.327  5506  5553 I jxcore-log: 
,11-25 12:44:55.328  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
11-25 12:44:55.328  5506  5553 I jxcore-log: 
,11-25 12:44:55.329   535   535 I ServiceManager: Waiting for service AtCmdFwd...
11-25 12:44:55.329  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
11-25 12:44:55.329  5506  5553 I jxcore-log: 
,11-25 12:44:55.330  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
11-25 12:44:55.330  5506  5553 I jxcore-log: 
,11-25 12:44:55.373  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:55.373  5506  5553 I jxcore-log: 
,11-25 12:44:55.376  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:55.376  5506  5553 I jxcore-log: 
,11-25 12:44:55.376  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:55.376  5506  5553 I jxcore-log: 
,11-25 12:44:55.377  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
11-25 12:44:55.377  5506  5553 I jxcore-log: 
11-25 12:44:55.377  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
11-25 12:44:55.377  5506  5553 I jxcore-log: 
11-25 12:44:55.378  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
11-25 12:44:55.378  5506  5553 I jxcore-log: 
,11-25 12:44:55.379  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:55.379  5506  5553 I jxcore-log: 
11-25 12:44:55.380  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
11-25 12:44:55.380  5506  5553 I jxcore-log: 
,11-25 12:44:55.380  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
11-25 12:44:55.380  5506  5553 I jxcore-log: 
11-25 12:44:55.380  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
11-25 12:44:55.380  5506  5553 I jxcore-log: 
11-25 12:44:55.381  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
11-25 12:44:55.381  5506  5553 I jxcore-log: 
,11-25 12:44:55.381  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
11-25 12:44:55.381  5506  5553 I jxcore-log: 
11-25 12:44:55.382  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
11-25 12:44:55.382  5506  5553 I jxcore-log: 
11-25 12:44:55.382  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
11-25 12:44:55.382  5506  5553 I jxcore-log: 
11-25 12:44:55.383  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
11-25 12:44:55.383  5506  5553 I jxcore-log: 
,11-25 12:44:55.383  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
11-25 12:44:55.383  5506  5553 I jxcore-log: 
11-25 12:44:55.384  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
11-25 12:44:55.384  5506  5553 I jxcore-log: 
,11-25 12:44:55.384  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
11-25 12:44:55.384  5506  5553 I jxcore-log: 
11-25 12:44:55.385  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
11-25 12:44:55.385  5506  5553 I jxcore-log: 
,11-25 12:44:55.385  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
11-25 12:44:55.385  5506  5553 I jxcore-log: 
,11-25 12:44:55.386  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
11-25 12:44:55.386  5506  5553 I jxcore-log: 
11-25 12:44:55.386  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
11-25 12:44:55.386  5506  5553 I jxcore-log: 
11-25 12:44:55.387  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
11-25 12:44:55.387  5506  5553 I jxcore-log: 
11-25 12:44:55.387  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
11-25 12:44:55.387  5506  5553 I jxcore-log: 
,11-25 12:44:55.387  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
11-25 12:44:55.387  5506  5553 I jxcore-log: 
11-25 12:44:55.388  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
11-25 12:44:55.388  5506  5553 I jxcore-log: 
11-25 12:44:55.388  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
11-25 12:44:55.388  5506  5553 I jxcore-log: 
11-25 12:44:55.389  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
11-25 12:44:55.389  5506  5553 I jxcore-log: 
,11-25 12:44:55.389  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
11-25 12:44:55.389  5506  5553 I jxcore-log: 
11-25 12:44:55.390  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
11-25 12:44:55.390  5506  5553 I jxcore-log: 
11-25 12:44:55.390  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
11-25 12:44:55.390  5506  5553 I jxcore-log: 
11-25 12:44:55.391  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
11-25 12:44:55.391  5506  5553 I jxcore-log: 
11-25 12:44:55.391  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
11-25 12:44:55.391  5506  5553 I jxcore-log: 
11-25 12:44:55.392  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
11-25 12:44:55.392  5506  5553 I jxcore-log: 
11-25 12:44:55.392  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
11-25 12:44:55.392  5506  5553 I jxcore-log: 
11-25 12:44:55.393  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
11-25 12:44:55.393  5506  5553 I jxcore-log: 
11-25 12:44:55.393  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
11-25 12:44:55.393  5506  5553 I jxcore-log: 
11-25 12:44:55.393  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
11-25 12:44:55.393  5506  5553 I jxcore-log: 
11-25 12:44:55.394  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
11-25 12:44:55.394  5506  5553 I jxcore-log: 
11-25 12:44:55.394  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
11-25 12:44:55.394  5506  5553 I jxcore-log: 
11-25 12:44:55.395  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
11-25 12:44:55.395  5506  5553 I jxcore-log: 
11-25 12:44:55.395  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
11-25 12:44:55.395  5506  5553 I jxcore-log: 
11-25 12:44:55.396  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
11-25 12:44:55.396  5506  5553 I jxcore-log: 
11-25 12:44:55.396  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
11-25 12:44:55.396  5506  5553 I jxcore-log: 
11-25 12:44:55.396  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
11-25 12:44:55.396  5506  5553 I jxcore-log: 
11-25 12:44:55.397  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
11-25 12:44:55.397  5506  5553 I jxcore-log: 
11-25 12:44:55.397  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
11-25 12:44:55.397  5506  5553 I jxcore-log: 
11-25 12:44:55.398  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
11-25 12:44:55.398  5506  5553 I jxcore-log: 
11-25 12:44:55.398  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
11-25 12:44:55.398  5506  5553 I jxcore-log: 
11-25 12:44:55.398  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
11-25 12:44:55.398  5506  5553 I jxcore-log: 
11-25 12:44:55.399  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
11-25 12:44:55.399  5506  5553 I jxcore-log: 
11-25 12:44:55.399  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
11-25 12:44:55.399  5506  5553 I jxcore-log: 
11-25 12:44:55.401  5506  5553 I jxcore-log: ok 28 native server is nulled out
11-25 12:44:55.401  5506  5553 I jxcore-log: 
11-25 12:44:55.402  5506  5553 I jxcore-log: ok 29 native server should be closed
11-25 12:44:55.402  5506  5553 I jxcore-log: 
11-25 12:44:55.402  5506  5553 I jxcore-log: ok 30 incoming has been removed
11-25 12:44:55.402  5506  5553 I jxcore-log: 
11-25 12:44:55.402  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
11-25 12:44:55.402  5506  5553 I jxcore-log: 
11-25 12:44:55.403  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
11-25 12:44:55.403  5506  5553 I jxcore-log: 
11-25 12:44:55.403  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
11-25 12:44:55.403  5506  5553 I jxcore-log: 
11-25 12:44:55.404  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
11-25 12:44:55.404  5506  5553 I jxcore-log: 
11-25 12:44:55.404  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
11-25 12:44:55.404  5506  5553 I jxcore-log: 
11-25 12:44:55.404  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
11-25 12:44:55.404  5506  5553 I jxcore-log: 
11-25 12:44:55.404  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
11-25 12:44:55.404  5506  5553 I jxcore-log: 
11-25 12:44:55.405  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
11-25 12:44:55.405  5506  5553 I jxcore-log: 
11-25 12:44:55.405  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
11-25 12:44:55.405  5506  5553 I jxcore-log: 
11-25 12:44:55.405  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:55.405  5506  5553 I jxcore-log: 
,11-25 12:44:55.448  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
11-25 12:44:55.448  5506  5553 I jxcore-log: 
11-25 12:44:55.448  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
11-25 12:44:55.448  5506  5553 I jxcore-log: 
11-25 12:44:55.448  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
11-25 12:44:55.448  5506  5553 I jxcore-log: 
11-25 12:44:55.449  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
11-25 12:44:55.449  5506  5553 I jxcore-log: 
11-25 12:44:55.449  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
11-25 12:44:55.449  5506  5553 I jxcore-log: 
11-25 12:44:55.449  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
11-25 12:44:55.449  5506  5553 I jxcore-log: 
11-25 12:44:55.450  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
11-25 12:44:55.450  5506  5553 I jxcore-log: 
11-25 12:44:55.450  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
11-25 12:44:55.450  5506  5553 I jxcore-log: 
11-25 12:44:55.450  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
11-25 12:44:55.450  5506  5553 I jxcore-log: 
11-25 12:44:55.450  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
11-25 12:44:55.450  5506  5553 I jxcore-log: 
11-25 12:44:55.450  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
11-25 12:44:55.450  5506  5553 I jxcore-log: 
11-25 12:44:55.451  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
11-25 12:44:55.451  5506  5553 I jxcore-log: 
11-25 12:44:55.451  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
11-25 12:44:55.451  5506  5553 I jxcore-log: 
11-25 12:44:55.451  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
11-25 12:44:55.451  5506  5553 I jxcore-log: 
11-25 12:44:55.451  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
11-25 12:44:55.451  5506  5553 I jxcore-log: 
11-25 12:44:55.451  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
11-25 12:44:55.451  5506  5553 I jxcore-log: 
11-25 12:44:55.451  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
11-25 12:44:55.451  5506  5553 I jxcore-log: 
11-25 12:44:55.452  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
11-25 12:44:55.452  5506  5553 I jxcore-log: 
11-25 12:44:55.452  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
11-25 12:44:55.452  5506  5553 I jxcore-log: 
11-25 12:44:55.452  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
11-25 12:44:55.452  5506  5553 I jxcore-log: 
11-25 12:44:55.452  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
11-25 12:44:55.452  5506  5553 I jxcore-log: 
11-25 12:44:55.452  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
11-25 12:44:55.452  5506  5553 I jxcore-log: 
11-25 12:44:55.453  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
11-25 12:44:55.453  5506  5553 I jxcore-log: 
11-25 12:44:55.453  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
11-25 12:44:55.453  5506  5553 I jxcore-log: 
11-25 12:44:55.453  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
11-25 12:44:55.453  5506  5553 I jxcore-log: 
11-25 12:44:55.453  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
11-25 12:44:55.453  5506  5553 I jxcore-log: 
11-25 12:44:55.453  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
11-25 12:44:55.453  5506  5553 I jxcore-log: 
11-25 12:44:55.454  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
11-25 12:44:55.454  5506  5553 I jxcore-log: 
11-25 12:44:55.454  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
11-25 12:44:55.454  5506  5553 I jxcore-log: 
11-25 12:44:55.454  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
11-25 12:44:55.454  5506  5553 I jxcore-log: 
11-25 12:44:55.454  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
11-25 12:44:55.454  5506  5553 I jxcore-log: 
11-25 12:44:55.454  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
11-25 12:44:55.454  5506  5553 I jxcore-log: 
11-25 12:44:55.454  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
11-25 12:44:55.454  5506  5553 I jxcore-log: 
11-25 12:44:55.455  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
11-25 12:44:55.455  5506  5553 I jxcore-log: 
11-25 12:44:55.457  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
11-25 12:44:55.457  5506  5553 I jxcore-log: 
11-25 12:44:55.458  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
11-25 12:44:55.458  5506  5553 I jxcore-log: 
11-25 12:44:55.458  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
11-25 12:44:55.458  5506  5553 I jxcore-log: 
11-25 12:44:55.458  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
11-25 12:44:55.458  5506  5553 I jxcore-log: 
11-25 12:44:55.458  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
11-25 12:44:55.458  5506  5553 I jxcore-log: 
11-25 12:44:55.459  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:55.459  5506  5553 I jxcore-log: 
,11-25 12:44:55.488  5506  5553 I jxcore-log: # teardown
11-25 12:44:55.488  5506  5553 I jxcore-log: 
,11-25 12:44:55.528  5506  5553 I jxcore-log: 2016-11-25 11:44:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:55.528  5506  5553 I jxcore-log: 
,11-25 12:44:55.544  5506  5553 I jxcore-log: # setup
11-25 12:44:55.544  5506  5553 I jxcore-log: 
,11-25 12:44:55.729   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:44:56.330   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:57.331   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:57.339  5506  5553 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
11-25 12:44:57.339  5506  5553 I jxcore-log: 
,11-25 12:44:57.475  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:57.475  5506  5553 I jxcore-log: 
,11-25 12:44:57.480  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'listening 38313'
11-25 12:44:57.480  5506  5553 I jxcore-log: 
,11-25 12:44:57.488  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:57.488  5506  5553 I jxcore-log: 
,11-25 12:44:57.491  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:57.491  5506  5553 I jxcore-log: 
,11-25 12:44:57.498  5506  5553 I jxcore-log: ok 31 we should not have gotten an error
11-25 12:44:57.498  5506  5553 I jxcore-log: 
,11-25 12:44:57.502  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:57.502  5506  5553 I jxcore-log: 
,11-25 12:44:57.510  5506  5553 I jxcore-log: ok 32 Buffers are identical
11-25 12:44:57.510  5506  5553 I jxcore-log: 
,11-25 12:44:57.511  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:57.511  5506  5553 I jxcore-log: 
11-25 12:44:57.513  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:57.513  5506  5553 I jxcore-log: 
,11-25 12:44:57.523  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:57.523  5506  5553 I jxcore-log: 
,11-25 12:44:57.524  5506  5553 I jxcore-log: ok 33 server should be fine
11-25 12:44:57.524  5506  5553 I jxcore-log: 
11-25 12:44:57.524  5506  5553 I jxcore-log: ok 34 server should be open
11-25 12:44:57.524  5506  5553 I jxcore-log: 
11-25 12:44:57.525  5506  5553 I jxcore-log: ok 35 incoming has been removed
11-25 12:44:57.525  5506  5553 I jxcore-log: 
11-25 12:44:57.525  5506  5553 I jxcore-log: ok 36 The mux object should be closed
11-25 12:44:57.525  5506  5553 I jxcore-log: 
11-25 12:44:57.525  5506  5553 I jxcore-log: ok 37 The mux stream should be closed
11-25 12:44:57.525  5506  5553 I jxcore-log: 
,11-25 12:44:57.530  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:57.530  5506  5553 I jxcore-log: 
,11-25 12:44:57.532  5506  5553 I jxcore-log: # teardown
11-25 12:44:57.532  5506  5553 I jxcore-log: 
,11-25 12:44:57.593  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:57.593  5506  5553 I jxcore-log: 
,11-25 12:44:57.594  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:57.594  5506  5553 I jxcore-log: 
11-25 12:44:57.596  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:57.596  5506  5553 I jxcore-log: 
,11-25 12:44:57.603  5506  5553 I jxcore-log: # setup
11-25 12:44:57.603  5506  5553 I jxcore-log: 
,11-25 12:44:57.669  5506  5553 I jxcore-log: # native server - timing out the incoming connection cleans everything up
11-25 12:44:57.669  5506  5553 I jxcore-log: 
,11-25 12:44:57.700  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'Creating Native Server'
11-25 12:44:57.700  5506  5553 I jxcore-log: 
,11-25 12:44:57.704  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'listening 47459'
11-25 12:44:57.704  5506  5553 I jxcore-log: 
,11-25 12:44:57.710  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
11-25 12:44:57.710  5506  5553 I jxcore-log: 
,11-25 12:44:57.711  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
11-25 12:44:57.711  5506  5553 I jxcore-log: 
,11-25 12:44:57.718  5506  5553 I jxcore-log: ok 38 we should not have gotten an error
11-25 12:44:57.718  5506  5553 I jxcore-log: 
,11-25 12:44:57.721  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
11-25 12:44:57.721  5506  5553 I jxcore-log: 
,11-25 12:44:57.729  5506  5553 I jxcore-log: ok 39 Buffers are identical
11-25 12:44:57.729  5506  5553 I jxcore-log: 
,11-25 12:44:57.732  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
11-25 12:44:57.732  5506  5553 I jxcore-log: 
,11-25 12:44:57.734  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
11-25 12:44:57.734  5506  5553 I jxcore-log: 
,11-25 12:44:57.735  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:57.735  5506  5553 I jxcore-log: 
,11-25 12:44:57.739  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
11-25 12:44:57.739  5506  5553 I jxcore-log: 
,11-25 12:44:57.740  5506  5553 I jxcore-log: ok 40 server should be fine
11-25 12:44:57.740  5506  5553 I jxcore-log: 
,11-25 12:44:57.740  5506  5553 I jxcore-log: ok 41 server should be open
11-25 12:44:57.740  5506  5553 I jxcore-log: 
11-25 12:44:57.741  5506  5553 I jxcore-log: ok 42 incoming has been removed
11-25 12:44:57.741  5506  5553 I jxcore-log: 
11-25 12:44:57.741  5506  5553 I jxcore-log: ok 43 The mux object should be closed
11-25 12:44:57.741  5506  5553 I jxcore-log: 
11-25 12:44:57.741  5506  5553 I jxcore-log: ok 44 The mux stream should be closed
11-25 12:44:57.741  5506  5553 I jxcore-log: 
,11-25 12:44:57.748  5506  5553 I jxcore-log: # teardown
11-25 12:44:57.748  5506  5553 I jxcore-log: 
,11-25 12:44:57.753  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
11-25 12:44:57.753  5506  5553 I jxcore-log: 
,11-25 12:44:57.769  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:57.769  5506  5553 I jxcore-log: 
,11-25 12:44:57.771  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:57.771  5506  5553 I jxcore-log: 
11-25 12:44:57.772  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG createNativeListener: 'Native Server - close'
11-25 12:44:57.772  5506  5553 I jxcore-log: 
,11-25 12:44:57.778  5506  5553 I jxcore-log: # setup
11-25 12:44:57.778  5506  5553 I jxcore-log: 
,11-25 12:44:57.807  5506  5553 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
11-25 12:44:57.807  5506  5553 I jxcore-log: 
,11-25 12:44:57.848  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:57.848  5506  5553 I jxcore-log: 
,11-25 12:44:57.953  5506  5553 I jxcore-log: 2016-11-25 11:44:57 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
11-25 12:44:57.953  5506  5553 I jxcore-log: 
,11-25 12:44:57.954  5506  5553 I jxcore-log: ok 45 Got right error
11-25 12:44:57.954  5506  5553 I jxcore-log: 
,11-25 12:44:57.958  5506  5553 I jxcore-log: # teardown
11-25 12:44:57.958  5506  5553 I jxcore-log: 
,11-25 12:44:58.025  5506  5553 I jxcore-log: 2016-11-25 11:44:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:58.025  5506  5553 I jxcore-log: 
,11-25 12:44:58.036  5506  5553 I jxcore-log: # setup
11-25 12:44:58.036  5506  5553 I jxcore-log: 
,11-25 12:44:58.121  5506  5553 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
11-25 12:44:58.121  5506  5553 I jxcore-log: 
,11-25 12:44:58.205  5506  5553 I jxcore-log: 2016-11-25 11:44:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
11-25 12:44:58.205  5506  5553 I jxcore-log: 
,11-25 12:44:58.207  5506  5553 I jxcore-log: ok 46 Got socket hang up
11-25 12:44:58.207  5506  5553 I jxcore-log: 
,11-25 12:44:58.212  5506  5553 I jxcore-log: # teardown
11-25 12:44:58.212  5506  5553 I jxcore-log: 
,11-25 12:44:58.248  5506  5553 I jxcore-log: 2016-11-25 11:44:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:58.248  5506  5553 I jxcore-log: 
,11-25 12:44:58.257  5506  5553 I jxcore-log: # setup
11-25 12:44:58.257  5506  5553 I jxcore-log: 
,11-25 12:44:58.318  5506  5553 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
11-25 12:44:58.318  5506  5553 I jxcore-log: 
,11-25 12:44:58.332   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:44:58.486  5506  5553 I jxcore-log: 2016-11-25 11:44:58 - DEBUG localSeqManager: 'Got an error trying to update seq []'
11-25 12:44:58.486  5506  5553 I jxcore-log: 
,11-25 12:44:58.487  5506  5553 I jxcore-log: ok 47 Got 500 as expected
11-25 12:44:58.487  5506  5553 I jxcore-log: 
,11-25 12:44:58.493  5506  5553 I jxcore-log: # teardown
11-25 12:44:58.493  5506  5553 I jxcore-log: 
,11-25 12:44:58.526  5506  5553 I jxcore-log: 2016-11-25 11:44:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
11-25 12:44:58.526  5506  5553 I jxcore-log: 
,11-25 12:44:58.537  5506  5553 I jxcore-log: # setup
11-25 12:44:58.537  5506  5553 I jxcore-log: 
,11-25 12:44:58.563  5506  5553 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
11-25 12:44:58.563  5506  5553 I jxcore-log: 
,11-25 12:44:59.333   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 12:45:00.391  5506  5553 I jxcore-log: ok 48 should be equal
11-25 12:45:00.391  5506  5553 I jxcore-log: 
,11-25 12:45:00.392  5506  5553 I jxcore-log: ok 49 revs are equal
11-25 12:45:00.392  5506  5553 I jxcore-log: 
,11-25 12:45:00.405  5506  5553 I jxcore-log: # teardown
11-25 12:45:00.405  5506  5553 I jxcore-log: 
,11-25 12:45:01.038   929   942 I ActivityManager: Start proc 5879:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,11-25 12:45:01.104  5879  5879 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,11-25 12:45:01.133  5879  5879 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
11-25 12:45:01.133  5879  5879 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-25 12:45:01.133  5879  5879 I GAv4    :   adb logcat -s GAv4
,11-25 12:45:01.147  5879  5879 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-25 12:45:01.153  5879  5879 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-25 12:45:01.169  5879  5894 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-25 12:45:01.176   929  3680 I ActivityManager: Killing 5381:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-25 12:45:07.013   929  2827 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 12:45:10.865   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:45:13.897   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:45:19.334   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:45:20.335   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:45:21.336   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:45:22.337   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:45:22.998   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:45:23.338   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 12:45:24.339   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 12:45:26.029   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:45:41.166   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:45:44.196   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:45:47.016   929  2827 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 12:45:49.340   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-25 12:45:49.340   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 12:45:56.288   929  2842 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 12:46:00.427  5506  5553 I jxcore-log: 2016-11-25 11:46:00 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
11-25 12:46:00.427  5506  5553 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
11-25 12:46:00.427  5506  5553 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
11-25 12:46:00.427  5506  5553 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
11-25 12:46:00.427  5506  5553 I jxcore-log:     at $9@timers.js:120:1
11-25 12:46:00.427  5506  5553 I jxcore-log: ''
11-25 12:46:00.427  5506  5553 I jxcore-log: 
,11-25 12:46:00.432  5506  5553 I jxcore-log: 2016-11-25 11:46:00 - DEBUG CoordinatedClient: 'test client failed'
11-25 12:46:00.432  5506  5553 I jxcore-log: 
,11-25 12:46:00.441  5506  5553 I jxcore-log: 2016-11-25 11:46:00 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-25 12:46:00.441  5506  5553 I jxcore-log: 
,11-25 12:46:00.449  5506  5553 I jxcore-log: 2016-11-25 11:46:00 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
11-25 12:46:00.449  5506  5553 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
11-25 12:46:00.449  5506  5553 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
11-25 12:46:00.449  5506  5553 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
11-25 12:46:00.449  5506  5553 I jxcore-log:     at $9@timers.js:120:1
11-25 12:46:00.449  5506  5553 I jxcore-log: ''
11-25 12:46:00.449  5506  5553 I jxcore-log: 
,11-25 12:46:00.451  5506  5553 I jxcore-log: 2016-11-25 11:46:00 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 12:46:00.451  5506  5553 I jxcore-log: 
,11-25 12:46:01.098  5898  5898 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 12:46:01.123  5898  5898 D AndroidRuntime: CheckJNI is OFF
,11-25 12:46:01.151  5898  5898 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 12:46:01.187  5898  5898 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 12:46:01.203  5898  5898 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 12:46:01.216   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-25 12:46:01.217   929   942 I ActivityManager: Killing 5506:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 12:46:01.264   929  2817 W InputDispatcher: channel '4e7859b com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-25 12:46:01.265   929  2817 E InputDispatcher: channel '4e7859b com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-25 12:46:01.270   929  3667 I WindowState: WIN DEATH: Window{4e7859b u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-25 12:46:01.270   929  3667 W InputDispatcher: Attempted to unregister already unregistered input channel '4e7859b com.test.thalitest/com.test.thalitest.MainActivity (server)'
11-25 12:46:01.270   929  2837 D WifiService: Client connection lost with reason: 4
,11-25 12:46:01.273   929  3680 D GraphicsStats: Buffer count: 2
,11-25 12:46:01.291   929   942 W ActivityManager: Force removing ActivityRecord{68bfbc0 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-25 12:46:01.368   929   952 I art     : Starting a blocking GC Explicit
,11-25 12:46:01.376   929  3739 W ActivityManager: Spurious death for ProcessRecord{ae60b15 0:com.test.thalitest/u0a77}, curProc for 5506: null
,11-25 12:46:01.409   929   939 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5506 uid 10077
11-25 12:46:01.408   939   939 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[26837]" dev="sockfs" ino=26837 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 12:46:01.408   939   939 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[26837]" dev="sockfs" ino=26837 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 12:46:01.411  3541  3541 I Keyboard.Facilitator: onFinishInput()
,11-25 12:46:01.472  3836  5910 I MicroRecognitionRnrImpl: Starting detection.
,11-25 12:46:01.473  3836  5911 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@1224a75
,11-25 12:46:01.475   512  5913 I AudioFlinger: AudioFlinger's thread 0xf1fc0000 ready to run
11-25 12:46:01.476   929   952 I art     : Explicit concurrent mark sweep GC freed 100652(6MB) AllocSpace objects, 50(1464KB) LOS objects, 33% free, 29MB/43MB, paused 1.694ms total 108.037ms
,11-25 12:46:01.479   512  2874 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-25 12:46:01.481  3836  5911 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@1224a75
,11-25 12:46:01.491   512  5913 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-25 12:46:01.491   512  5913 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-25 12:46:01.491   512  5913 I ACDB-LOADER: ACDB AFE returned = -19
11-25 12:46:01.491   512  5913 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-25 12:46:01.491   512  5913 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-25 12:46:01.491   512  5913 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-25 12:46:01.498   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-25 12:46:01.499   512  5913 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-25 12:46:01.501  5898  5898 I art     : System.exit called, status: 0
,11-25 12:46:01.501  5898  5898 I AndroidRuntime: VM exiting with result code 0.
,11-25 12:46:01.515   929   952 I ActivityManager: Start proc 5915:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-25 12:46:01.515   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 12:46:01.523  3541  3541 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-25 12:46:01.525  5774  5774 D BluetoothMapAppObserver: onReceive
11-25 12:46:01.525  5774  5774 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-25 12:46:01.528  3916  4034 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-25 12:46:01.537  3541  5926 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 12:46:01.543   929  2818 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-25 12:46:01.547  3541  5926 I Decoder : createOrResetDecoder
,11-25 12:46:01.559  3276  5929 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 12:46:01.582  3836  3836 I HotwordWorkerImpl: onReady
,11-25 12:46:01.587   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 12:46:01.591  3657  3657 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 12:46:01.598  3453  3453 I ConfigService: onCreate
,11-25 12:46:01.614    29    29 W kworker/3:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 12:46:01.618    29    29 W kworker/3:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 12:46:01.634  3541  5926 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-25 12:46:01.635  3681  3824 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-25 12:46:01.639  3453  3453 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,11-25 12:46:01.640  3453  3453 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
11-25 12:46:01.640  3453  3453 E AndroidRuntime: FATAL EXCEPTION: main
11-25 12:46:01.640  3453  3453 E AndroidRuntime: Process: com.google.process.gapps, PID: 3453
11-25 12:46:01.640  3453  3453 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-25 12:46:01.640  3453  3453 E AndroidRuntime: 	... 8 more
,11-25 12:46:01.638    29    29 W kworker/3:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 12:46:01.654   929  3293 I ActivityManager: Start proc 5936:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-25 12:46:01.654  3681  3824 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-25 12:46:01.654  3681  3824 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3681
11-25 12:46:01.654  3681  3824 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:46:01.654  3681  3824 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 12:46:01.660   929  5948 E DropBoxManagerService: Can't write: system_app_crash
11-25 12:46:01.660   929  5948 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 12:46:01.660   929  5948 E DropBoxManagerService: 	... 5 more
,11-25 12:46:01.661  3276  5929 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-25 12:46:01.661   929  3680 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-25 12:46:01.662   929  5946 E DropBoxManagerService: Can't write: system_app_crash
11-25 12:46:01.662   929  5946 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 12:46:01.662   929  5946 E DropBoxManagerService: 	... 5 more
,11-25 12:46:01.665  3836  3855 W SearchService: Abort, client detached.
11-25 12:46:01.667  3836  3836 I HotwordDetector: Closing mic
,11-25 12:46:01.667  3836  4095 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1224a75
11-25 12:46:01.668  3836  5911 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-25 12:46:01.678   710   710 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[35090]" dev="sockfs" ino=35090 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 12:46:01.681   710   710 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[35090]" dev="sockfs" ino=35090 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 12:46:01.681   402   402 W Binder_1: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31568]" dev="sockfs" ino=31568 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 12:46:01.681   402   402 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[31568]" dev="sockfs" ino=31568 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-25 12:46:01.684   929  5950 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-25 12:46:01.686  3276  5929 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-25 12:46:01.686  3276  5929 E AndroidRuntime: Process: android.process.acore, PID: 3276
11-25 12:46:01.686  3276  5929 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 12:46:01.686  3276  5929 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 12:46:01.692   929  5951 E DropBoxManagerService: Can't write: system_app_crash
11-25 12:46:01.692   929  5951 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 12:46:01.692   929  5951 E DropBoxManagerService: 	... 5 more
,11-25 12:46:01.720  3541  5926 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-25 12:46:01.723  3541  5926 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-25 12:46:01.723  3541  5926 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-25 12:46:01.725  3541  5926 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-25 12:46:01.725  3541  5926 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-25 12:46:01.725  3541  5926 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-25 12:46:01.725  3541  5926 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,11-25 12:46:01.726  3541  5926 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-25 12:46:01.729  3541  5926 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-25 12:46:01.729  3541  5926 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-25 12:46:01.729  3541  5926 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-25 12:46:01.729  3541  5926 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-25 12:46:01.729  3541  5926 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-25 12:46:01.737   512  5913 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-25 12:46:01.738   512  5913 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-25 12:46:01.743   512  5913 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,11-25 12:46:01.743   512  5913 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-25 12:46:01.744   512  2874 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-25 12:46:01.747  3836  4101 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-25 12:46:01.747  3836  5910 I MicroRecognitionRnrImpl: Detection finished
,11-25 12:46:02.040   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
