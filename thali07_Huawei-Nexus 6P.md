#### Test 9504761598f4ffc_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 10:32:33.576  3796  4153 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-24 10:32:33.656  3796  4153 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-24 10:32:34.038  5523  5523 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 10:32:34.043  5523  5523 D AndroidRuntime: CheckJNI is OFF
11-24 10:32:34.072  5523  5523 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 10:32:34.104  5523  5523 I Radio-JNI: register_android_hardware_Radio DONE
11-24 10:32:34.119  5523  5523 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 10:32:34.131   932  3506 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 10:32:34.150  5523  5523 D AndroidRuntime: Shutting down VM
11-24 10:32:34.157  3904  3917 W SearchService: Abort, client detached.
11-24 10:32:34.169  3904  4114 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2b8f7ef
11-24 10:32:34.169  3904  3904 I HotwordDetector: Closing mic
11-24 10:32:34.169  3904  4140 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 10:32:34.186   932   943 I ActivityManager: Start proc 5532:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 10:32:34.251   514  4142 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 10:32:34.252   514  4142 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 10:32:34.256   514  4142 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 10:32:34.256   514  4142 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 10:32:34.258   514  2930 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 10:32:34.260  3904  4129 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 10:32:34.261  3904  4139 I MicroRecognitionRnrImpl: Detection finished
11-24 10:32:34.281  5532  5532 I CordovaLog: Changing log level to DEBUG(3)
11-24 10:32:34.281  5532  5532 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 10:32:34.281  5532  5532 D CordovaActivity: CordovaActivity.onCreate()
11-24 10:32:34.285  5532  5532 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 10:32:34.305  5532  5532 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-24 10:32:34.363  5532  5532 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 9263-9317)
11-24 10:32:34.363  5532  5532 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 10:32:34.397  5532  5532 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c2dfbcc}
11-24 10:32:34.397  5532  5532 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 10:32:34.397  5532  5532 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 10:32:34.401  5532  5532 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 10:32:34.401  5532  5532 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 10:32:34.468  5532  5532 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 10:32:34.477  5532  5532 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 10:32:34.477  5532  5532 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 10:32:34.477  5532  5532 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 10:32:34.477  5532  5532 I Adreno  : Build Date                       : 12/06/15
11-24 10:32:34.477  5532  5532 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 10:32:34.477  5532  5532 I Adreno  : Local Branch                     : mybranch17112971
11-24 10:32:34.477  5532  5532 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 10:32:34.477  5532  5532 I Adreno  : Remote Branch                    : NONE
11-24 10:32:34.477  5532  5532 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 10:32:34.516   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a27f9d:true
,11-24 10:32:34.543   751   751 W Binder_3: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[16799]" dev="sockfs" ino=16799 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 10:32:34.543   751   751 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[16799]" dev="sockfs" ino=16799 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:32:34.554  5532  5532 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 10:32:34.562  5532  5532 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 10:32:34.565  5532  5532 D PluginManager: init()
,11-24 10:32:34.568  5532  5532 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 10:32:34.664  5532  5532 D CordovaActivity: Started the activity.
,11-24 10:32:34.664  5532  5532 D CordovaActivity: Resumed the activity.
,11-24 10:32:34.667   751   751 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32075]" dev="sockfs" ino=32075 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:32:34.667   751   751 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32075]" dev="sockfs" ino=32075 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 10:32:34.670  5532  5569 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 10:32:34.670  3722  3722 W Binder_7: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22449]" dev="sockfs" ino=22449 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 10:32:34.670  3722  3722 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22449]" dev="sockfs" ino=22449 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 10:32:34.675  5532  5556 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 10:32:34.700  5532  5569 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 10:32:34.778   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +618ms
,11-24 10:32:34.780  3593  3593 I Keyboard.Facilitator: onFinishInput()
11-24 10:32:34.773  3727  3727 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32078]" dev="sockfs" ino=32078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 10:32:34.773  3727  3727 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32078]" dev="sockfs" ino=32078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 10:32:34.777  3530  3530 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32077]" dev="sockfs" ino=32077 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 10:32:34.777  3530  3530 W Binder_6: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32077]" dev="sockfs" ino=32077 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 10:32:34.798  5532  5532 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 10:32:34.827  5532  5532 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5532
,11-24 10:32:34.934  5532  5532 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 10:32:35.113  5532  5571 D jxcore_app_log: JniHelper::setJavaVM(0xf543c000), pthread_self() = -579864272
,11-24 10:32:35.118  5532  5571 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 10:32:35.118  5532  5571 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 10:32:35.118  5532  5571 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 10:32:35.118  5532  5571 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 10:32:35.118  5532  5571 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 10:32:35.118  5532  5571 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eea2e53 added. We now have 1 listener(s)
,11-24 10:32:35.129  5532  5571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-24 10:32:35.129  5532  5571 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:32:35.130  5532  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 10:32:35.130  5532  5571 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 10:32:35.132  5532  5571 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b22dc8e added. We now have 1 listener(s)
11-24 10:32:35.132  5532  5571 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:32:35.137   932  2909 D WifiService: New client listening to asynchronous messages
,11-24 10:32:35.138  5532  5571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 10:32:35.138  5532  5571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 10:32:35.138  5532  5571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 10:32:35.138  5532  5571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 10:32:35.138  5532  5571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 10:32:35.139  5532  5571 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 10:32:35.139  5532  5571 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 10:32:35.142  5532  5571 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 10:32:35.288  5532  5532 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 10:32:35.292  5532  5532 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-24 10:32:35.292  5532  5532 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 10:32:35.641  5532  5541 I art     : Background sticky concurrent mark sweep GC freed 76440(7MB) AllocSpace objects, 16(1076KB) LOS objects, 23% free, 25MB/32MB, paused 1.692ms total 280.562ms
,11-24 10:32:35.651   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:32:36.006  5532  5580 W jxcore-log: Initializing JXcore engine
11-24 10:32:36.006  5532  5580 W jxcore-log: JXcore engine is ready
,11-24 10:32:36.027  5580  5580 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12560 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 10:32:36.027  5580  5580 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14414]" dev="sockfs" ino=14414 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 10:32:36.027  5580  5580 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 10:32:36.027  5580  5580 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33143]" dev="sockfs" ino=33143 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 10:32:36.038  5532  5580 W jxcore-log: Starting JXcore engine
,11-24 10:32:36.089  5532  5580 W jxcore-log: Platform android
11-24 10:32:36.089  5532  5580 W jxcore-log: 
,11-24 10:32:36.089  5532  5580 W jxcore-log: Process ARCH arm
11-24 10:32:36.089  5532  5580 W jxcore-log: 
,11-24 10:32:36.271  5532  5580 I jxcore-log: JXcore Cordova bridge is ready!
11-24 10:32:36.271  5532  5580 I jxcore-log: 
11-24 10:32:36.271  5532  5580 W jxcore-log: JXcore engine is started
,11-24 10:32:36.287  5532  5571 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 10:32:36.296  5532  5532 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 10:32:36.296  5532  5532 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 10:32:37.720  3514  3514 I ConfigService: onDestroy
,11-24 10:32:38.337   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:32:39.179   932  3761 I ActivityManager: Killing 5172:org.codeaurora.ims/1001 (adj 15): empty #17
,11-24 10:32:39.229   932  3761 I ActivityManager: Killing 5082:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-24 10:32:39.338   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:32:40.338   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:32:41.340   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:32:42.343   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:32:43.344   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 10:32:46.011  5532  5580 I jxcore-log: 2016-11-24 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 10:32:46.011  5532  5580 I jxcore-log: 
,11-24 10:32:46.013  5532  5580 I jxcore-log: 2016-11-24 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 10:32:46.013  5532  5580 I jxcore-log: 
,11-24 10:32:46.021  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:32:46.021  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:32:46.023  5532  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 10:32:46.025  5532  5580 I jxcore-log: 2016-11-24 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 10:32:46.025  5532  5580 I jxcore-log: 
,11-24 10:32:46.027  5532  5580 I jxcore-log: 2016-11-24 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 10:32:46.027  5532  5580 I jxcore-log: 
,11-24 10:32:46.274  5532  5580 I jxcore-log: 2016-11-24 09:32:46 - DEBUG UnitTest_app: 'Running unit tests'
11-24 10:32:46.274  5532  5580 I jxcore-log: 
,11-24 10:32:46.275  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:32:46.275  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bb00ca added. We now have 2 listener(s)
11-24 10:32:46.276  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:32:46.276  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 10:32:46.276  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:32:46.276  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:32:46.276  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e19123b added. We now have 2 listener(s)
,11-24 10:32:46.276  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:32:46.277  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 10:32:46.278  5532  5580 D executeNativeTests: Running unit tests
,11-24 10:32:46.320  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:32:46.320  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 added. We now have 3 listener(s)
11-24 10:32:46.321  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:32:46.321  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:32:46.321  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 10:32:46.321  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:32:46.321  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 added. We now have 3 listener(s)
11-24 10:32:46.321  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:32:46.321  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:32:46.324  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 10:32:46.324  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:32:46.324  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:32:46.324  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:32:46.325  5532  5580 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 10:32:46.325  5532  5580 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 10:32:46.325  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 10:32:46.325  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 10:32:46.325  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:32:46.325  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:32:46.325  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:32:46.325  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:32:46.325  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:32:46.326  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:32:46.326  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:32:46.326  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:32:46.326  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 removed from the list
,11-24 10:32:46.326  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:46.327  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 removed from the list
11-24 10:32:46.327  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:32:46.327  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:46.327  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.327  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.327  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.327  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.327  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 10:32:46.327  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:32:46.328  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:46.328  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:46.328  5532  5580 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 10:32:46.329  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:32:46.329  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:32:46.329  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:32:46.329  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:32:46.329  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:32:46.329  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:32:46.329  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:46.329  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:46.329  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:32:46.329  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.329  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:46.330  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.330  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.330  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.330  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:32:46.330  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:32:46.330  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:46.330  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 10:32:46.332  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 10:32:46.333  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:32:46.333  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:32:46.333  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:32:46.333  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:32:46.333  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:32:46.333  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:32:46.333  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:32:46.333  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:46.333  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:32:46.333  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.333  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.334  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.334  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.334  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.334  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:32:46.334  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:32:46.334  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:46.334  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:46.334  5532  5580 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 10:32:46.336  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:32:46.336  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:32:46.341  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:32:46.342  5532  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 10:32:46.342  5532  5580 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 10:32:46.342  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:32:46.342  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:32:46.343  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:32:46.343  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:32:46.343  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 10:32:46.345  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:32:46.345  5532  5580 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:32:46.345  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 10:32:46.346  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:32:46.347  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.347  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:32:46.348  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:32:46.348  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:32:46.348  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 10:32:46.350  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 10:32:46.351  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:32:46.351  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 10:32:46.351  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.351  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:32:46.351  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:32:46.351  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:32:46.351  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:32:46.351  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.352  5532  5580 D BluetoothAdapter: STATE_ON
,11-24 10:32:46.354  4580  4593 D BtGatt.GattService: registerClient() - UUID=53cf01b4-e6d8-4f03-b3a0-2adef6083962
,11-24 10:32:46.355  4580  4655 D BtGatt.GattService: onClientRegistered() - UUID=53cf01b4-e6d8-4f03-b3a0-2adef6083962, clientIf=5
,11-24 10:32:46.356  5532  5572 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 10:32:46.357  4580  4792 D BtGatt.GattService: start scan with filters
,11-24 10:32:46.362  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 10:32:46.362  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.362  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:32:46.362  4580  4658 D BtGatt.ScanManager: handling starting scan
11-24 10:32:46.362  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.363  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 10:32:46.363  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 10:32:46.363  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:32:46.363  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.363  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.364  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:32:46.364  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:32:46.364  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.364  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.364  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.364  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.364  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:46.364  5532  5580 I io.jxcore.node.ConnectionHelper: start: OK
11-24 10:32:46.365  4580  4658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:32:46.365  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.365  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 10:32:46.365  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.369  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.370  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:32:46.370  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.370  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:46.370  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:32:46.372  4580  4655 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:32:46.372  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:46.372  4580  4658 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 10:32:46.378  4580  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:32:46.378  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:32:46.379  4580  4658 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:32:46.379  4580  4658 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 10:32:46.389  4580  4655 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:32:46.389  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:32:46.394  4580  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 10:32:46.394  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:32:46.761   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:32:46.871  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 10:32:46.872  5532  5532 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 10:32:46.872  5532  5532 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 10:32:51.369  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:32:51.369  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:32:51.369  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:32:51.369  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:32:51.370  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 10:32:51.370  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:32:51.370  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 10:32:51.370  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:32:51.370  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:51.370  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:32:51.370  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:32:51.371  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.371  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:51.371  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.372  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:32:51.372  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.373  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:32:51.373  4580  4593 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:32:51.374  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:32:51.375  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:32:51.376  4580  4658 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:32:51.376  4580  4800 D BtGatt.GattService: stopScan() - queue size =1
11-24 10:32:51.377  4580  4591 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:32:51.377  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:32:51.377  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.377  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:32:51.378  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.378  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.378  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:51.378  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.378  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:32:51.379  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.379  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.379  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.379  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:32:51.380  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:32:51.380  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 10:32:51.381  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.382  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.383  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:32:51.383  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.383  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:51.383  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:32:51.383  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:32:51.383  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:32:51.383  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:32:51.383  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:32:51.383  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:32:51.384  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:51.384  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:32:51.384  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:51.384  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:32:51.384  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:32:51.384  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-24 10:32:51.384  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:32:51.384  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:32:51.385  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:32:51.385  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:32:51.385  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 10:32:51.385  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:32:51.386  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:32:51.386  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:32:51.386  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:32:51.389  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 10:32:51.390  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:51.390  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:51.391  4580  4580 D BtGatt.ScanManager: awakened up at time 96346
,11-24 10:32:51.454  4580  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 10:32:51.454  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:51.454  4580  4655 D BtGatt.GattService: current time is 96409232080
11-24 10:32:51.455  4580  4655 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -86, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -86, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -90, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
11-24 10:32:51.456  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 10:32:51.457  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 10:32:51.458  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 10:32:51.458  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 10:32:51.458  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 10:32:51.458  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,11-24 10:32:51.464  4580  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 10:32:51.464  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:51.464  4580  4658 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:32:51.469  4580  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 10:32:51.469  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:51.469  4580  4658 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:32:51.473  4580  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:32:51.473  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:51.474  3904  5581 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 10:32:51.535  4774  4822 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-24 10:32:51.536  4774  4774 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 10:32:51.887  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:32:52.822   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:32:55.655   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:32:56.393  5532  5580 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 10:32:56.398  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 10:32:56.399  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:32:56.418  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 10:32:56.420  5532  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 10:32:56.421  5532  5580 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 10:32:56.421  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:32:56.421  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-24 10:32:56.421  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-24 10:32:56.421  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:32:56.421  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 10:32:56.425  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:32:56.427  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 10:32:56.427  5532  5580 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 10:32:56.427  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 10:32:56.430  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:32:56.433  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.433  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:32:56.434  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 10:32:56.434  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:32:56.434  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 10:32:56.439  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.439  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 10:32:56.439  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:32:56.439  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:32:56.439  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:32:56.440  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.440  5532  5580 D BluetoothAdapter: STATE_ON
,11-24 10:32:56.443  4580  4800 D BtGatt.GattService: registerClient() - UUID=4d77cefa-54eb-4532-98ee-187653aa4f27
11-24 10:32:56.444  4580  4655 D BtGatt.GattService: onClientRegistered() - UUID=4d77cefa-54eb-4532-98ee-187653aa4f27, clientIf=5
,11-24 10:32:56.444  5532  5542 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:32:56.445  4580  4591 D BtGatt.GattService: start scan with filters
11-24 10:32:56.448  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:32:56.448  4580  4658 D BtGatt.ScanManager: handling starting scan
11-24 10:32:56.448  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.448  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 10:32:56.448  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.448  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:32:56.448  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:32:56.449  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.449  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:32:56.449  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:32:56.449  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.449  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-24 10:32:56.449  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.449  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.451  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:32:56.451  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.454  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.454  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:32:56.454  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.454  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.454  5532  5580 I io.jxcore.node.ConnectionHelper: start: OK
,11-24 10:32:56.454  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 10:32:56.457  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 10:32:56.457  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.457  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.457  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:32:56.457  4580  4655 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:32:56.458  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.458  4580  4658 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:32:56.458  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:32:56.458  5532  5580 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 10:32:56.458  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:32:56.458  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:32:56.458  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:32:56.458  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 10:32:56.458  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:32:56.458  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 10:32:56.458  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:32:56.459  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.459  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:32:56.459  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:32:56.459  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.459  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.459  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.459  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:32:56.459  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.460  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:32:56.460  4580  4591 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:32:56.460  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:32:56.461  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:32:56.462  4580  4800 D BtGatt.GattService: stopScan() - queue size =1
,11-24 10:32:56.462  4580  4792 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:32:56.463  4580  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.463  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.463  4580  4658 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.463  4580  4658 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:32:56.463  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.464  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.464  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.464  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:32:56.464  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:32:56.464  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:32:56.464  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.466  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.466  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 10:32:56.466  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.466  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.466  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:32:56.466  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:32:56.466  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:32:56.466  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:32:56.466  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:32:56.466  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 10:32:56.466  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:32:56.466  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:32:56.467  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:56.467  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 10:32:56.467  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:56.467  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:32:56.467  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:32:56.467  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:32:56.467  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:32:56.467  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.467  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.467  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 10:32:56.467  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:32:56.467  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.467  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.470  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.470  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.470  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.470  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.470  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.471  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.471  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.471  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.471  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:32:56.471  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:32:56.471  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:32:56.471  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:32:56.472  5532  5580 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 10:32:56.474  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:32:56.474  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 10:32:56.475  4580  4655 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 10:32:56.475  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.480  4580  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:32:56.480  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:32:56.481  4580  4658 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:32:56.482  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 10:32:56.484  5532  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 10:32:56.485  5532  5580 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 10:32:56.485  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:32:56.485  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:32:56.485  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:32:56.485  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:32:56.485  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 10:32:56.486  4580  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:32:56.486  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:32:56.486  4580  4655 E BtGatt.ContextMap: Context not found for ID 5
11-24 10:32:56.487  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:32:56.489  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 10:32:56.489  5532  5580 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:32:56.489  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 10:32:56.490  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:32:56.492  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.492  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:32:56.493  4580  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 10:32:56.493  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.493  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:32:56.493  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:32:56.493  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 10:32:56.493  4580  4658 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:32:56.496  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.496  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:32:56.496  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:32:56.496  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:32:56.496  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:32:56.496  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.497  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:32:56.498  4580  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 10:32:56.498  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.498  4580  4658 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:32:56.498  4580  4792 D BtGatt.GattService: registerClient() - UUID=d6790c26-3a33-4a07-ac64-8b1612bbad86
11-24 10:32:56.499  4580  4655 D BtGatt.GattService: onClientRegistered() - UUID=d6790c26-3a33-4a07-ac64-8b1612bbad86, clientIf=5
,11-24 10:32:56.499  5532  5572 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 10:32:56.499  4580  4800 D BtGatt.GattService: start scan with filters
,11-24 10:32:56.502  4580  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:32:56.502  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:32:56.502  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.502  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:32:56.503  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:32:56.503  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.503  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 10:32:56.503  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 10:32:56.503  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.503  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:32:56.503  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:32:56.503  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.503  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.504  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.504  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.504  4580  4658 D BtGatt.ScanManager: handling starting scan
11-24 10:32:56.504  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:32:56.505  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.508  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.508  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:32:56.508  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.508  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:32:56.508  5532  5580 I io.jxcore.node.ConnectionHelper: start: OK
11-24 10:32:56.508  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.510  4580  4655 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:32:56.510  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.510  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.510  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.511  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:32:56.511  4580  4658 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:32:56.511  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:32:56.515  4580  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:32:56.515  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:32:56.515  4580  4658 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:32:56.515  4580  4658 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 10:32:56.523  4580  4655 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 10:32:56.523  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:32:56.527  4580  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:32:56.527  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:32:57.012  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 10:32:57.013  5532  5532 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 10:32:57.013  5532  5532 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 10:32:58.861   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:32:58.864   932  2910 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-24 10:33:00.007   932   932 I ActivityManager: Killing 5213:com.android.settings/1000 (adj 15): empty #17
,11-24 10:33:01.509  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:33:01.509  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:33:01.509  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:33:01.510  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:33:01.510  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 10:33:01.510  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:01.510  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 10:33:01.510  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:33:01.510  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.511  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 10:33:01.511  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:33:01.511  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.511  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.511  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.512  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:33:01.512  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.514  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:33:01.515  4580  4593 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:33:01.515  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:33:01.517  4580  4658 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:33:01.517  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:33:01.519  4580  4792 D BtGatt.GattService: stopScan() - queue size =1
,11-24 10:33:01.521  4580  4591 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:33:01.522  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 10:33:01.522  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.522  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:33:01.523  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:01.523  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.523  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.523  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.523  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 10:33:01.524  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.524  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.524  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.524  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:33:01.524  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:33:01.524  4580  4580 D BtGatt.ScanManager: awakened up at time 106479
,11-24 10:33:01.526  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:33:01.526  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.529  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.530  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:33:01.530  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:01.530  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:01.530  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:33:01.530  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:33:01.530  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:33:01.530  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:33:01.530  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:33:01.530  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-24 10:33:01.531  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:33:01.531  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:33:01.531  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:33:01.531  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:33:01.531  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:33:01.531  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 10:33:01.533  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:33:01.533  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:33:01.533  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 10:33:01.544  4580  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-24 10:33:01.544  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:33:01.544  4580  4655 D BtGatt.GattService: current time is 106498614338
11-24 10:33:01.544  4580  4655 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -88, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -87, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -87, 87, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -77, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 10:33:01.544  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 10:33:01.545  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 10:33:01.545  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 10:33:01.545  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 10:33:01.545  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 10:33:01.546  4580  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 10:33:01.552  4580  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 10:33:01.553  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:33:01.553  4580  4658 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:33:01.559  4580  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 10:33:01.559  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:33:01.559  4580  4658 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:33:01.564  4580  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:33:01.564  4580  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:33:01.887   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:33:01.898   932  2910 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-24 10:33:02.032  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:33:02.032  5532  5532 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:02.032  5532  5532 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 10:33:04.922   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:33:06.531  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:33:06.532  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.532  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.532  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 10:33:06.533  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 10:33:06.533  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:33:06.533  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.533  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.533  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.534  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.534  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.534  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 10:33:06.537  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.538  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.540  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.540  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.540  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.540  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.541  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.541  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.541  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.543  5532  5580 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-24 10:33:06.544  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.544  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.545  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:33:06.545  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.545  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.545  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.545  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.546  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.546  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.546  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.546  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.550  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.550  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.550  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.550  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.551  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.551  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.551  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:06.553  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 10:33:06.553  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.553  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:33:06.554  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.554  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.554  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.554  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.554  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.554  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:06.554  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.555  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.555  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.557  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.557  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.557  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.557  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.557  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.557  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.557  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.558  5532  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-24 10:33:06.559  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.559  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.559  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.559  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.559  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:33:06.559  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.560  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.560  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.560  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.560  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.560  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.563  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.563  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.563  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.563  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.563  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.563  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.563  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.564  5532  5580 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-24 10:33:06.565  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.565  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.565  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.565  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.565  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:33:06.565  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.566  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.566  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.566  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.566  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.566  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.568  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.568  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.568  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.568  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.568  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.568  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.569  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.570  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 10:33:06.570  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:33:06.570  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:33:06.570  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 10:33:06.570  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 10:33:06.571  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:33:06.571  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 10:33:06.571  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:33:06.571  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:33:06.571  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.571  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.571  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.572  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.572  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:33:06.572  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.572  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.572  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.572  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.572  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.572  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.574  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.574  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.575  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.575  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.575  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.575  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.575  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.576  5532  5580 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:33:06.577  5532  5580 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 10:33:06.577  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 10:33:06.582  5532  5580 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:33:06.582  5532  5580 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 10:33:06.582  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-24 10:33:06.583  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 10:33:06.584  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 10:33:06.584  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 10:33:06.584  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 10:33:06.584  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 10:33:06.584  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-24 10:33:06.584  5532  5580 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 10:33:06.584  5532  5580 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 10:33:06.584  5532  5580 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 10:33:06.584  5532  5580 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:33:06.585  5532  5580 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 10:33:06.585  5532  5580 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-24 10:33:06.585  5532  5580 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:33:06.585  5532  5580 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 10:33:06.585  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-24 10:33:06.592  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-24 10:33:06.593  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 10:33:06.594  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 10:33:06.594  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 10:33:06.594  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 10:33:06.595  5532  5580 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 10:33:06.595  5532  5580 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:33:06.595  5532  5580 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 10:33:06.595  5532  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-24 10:33:06.596  5532  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 10:33:06.596  5532  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 10:33:06.596  5532  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 10:33:06.596  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.596  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.596  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.596  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.596  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.597  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 10:33:06.597  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.598  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.598  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.598  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.598  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.598  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.598  5532  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-24 10:33:06.599  5532  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-24 10:33:06.597  4593  4593 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32117]" dev="sockfs" ino=32117 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 10:33:06.599  5532  5585 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 10:33:06.599  5532  5585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:06.600  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.600  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.600  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.600  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 10:33:06.600  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.600  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.600  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.597  4593  4593 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32117]" dev="sockfs" ino=32117 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 10:33:06.601  5532  5580 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 10:33:06.602  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:33:06.603  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.603  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.603  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.603  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.603  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.603  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.603  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.603  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.603  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.603  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.606  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.606  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.606  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.606  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.606  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.606  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.606  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:06.608  5532  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 10:33:06.608  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.608  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:33:06.608  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:33:06.609  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.609  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.609  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.609  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.609  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.609  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.609  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:06.609  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.611  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.611  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.611  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.611  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:06.611  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.612  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.612  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.613  5532  5580 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 10:33:06.613  5532  5580 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,11-24 10:33:06.613  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-24 10:33:06.614  5532  5580 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-24 10:33:06.614  5532  5580 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 10:33:06.614  5532  5580 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 10:33:06.615  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 10:33:06.615  5532  5580 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 10:33:06.615  5532  5580 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 10:33:06.615  5532  5580 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 10:33:06.615  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 10:33:06.615  5532  5580 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-24 10:33:06.615  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:06.615  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:06.615  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:06.615  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.615  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.615  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.615  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.615  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.615  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:06.616  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.616  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.617  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.617  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.617  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:06.617  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 10:33:06.617  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:06.617  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:06.618  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.618  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:06.618  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:06.618  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:06.618  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:06.618  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:06.618  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:33:07.957   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:33:08.345   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-24 10:33:08.345   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 10:33:11.619  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:11.620  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:11.620  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 10:33:11.620  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:11.620  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
,11-24 10:33:11.621  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:11.621  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:33:11.621  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:11.621  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:11.621  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:33:11.622  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:11.622  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:11.622  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:11.622  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:11.623  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.623  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.628  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.628  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.628  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.629  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:11.629  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:11.629  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:11.629  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:11.632  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 10:33:11.633  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:33:11.633  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 10:33:11.638  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 10:33:11.640  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-24 10:33:11.640  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 10:33:11.640  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 10:33:11.641  5532  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 10:33:11.641  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-24 10:33:11.641  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 10:33:11.641  5532  5532 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 10:33:11.641  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:11.642  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 10:33:11.642  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-24 10:33:11.642  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 10:33:11.642  5532  5587 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:11.642  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:33:11.643  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 10:33:11.644  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 10:33:11.644  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:11.644  5532  5532 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 10:33:11.644  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.644  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:33:11.644  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.644  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:33:11.644  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:33:11.645  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.643  4792  4792 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33899]" dev="sockfs" ino=33899 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 10:33:11.643  4792  4792 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33899]" dev="sockfs" ino=33899 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 10:33:11.646  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.647  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:33:11.647  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.647  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.647  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:11.647  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:33:11.647  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:11.647  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:33:11.647  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:11.647  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:33:11.648  5532  5587 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-24 10:33:11.648  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:11.648  5532  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 10:33:11.648  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:11.648  5532  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 10:33:11.648  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-24 10:33:11.648  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:11.648  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.648  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:11.648  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:11.648  5532  5532 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-24 10:33:11.648  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.648  5532  5532 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:11.649  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.650  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.651  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.651  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.651  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:11.651  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:11.651  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.651  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:11.653  5532  5580 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-24 10:33:11.653  5532  5580 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 10:33:11.654  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 10:33:11.654  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:33:11.654  5532  5580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:33:11.654  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:33:11.654  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:11.654  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:11.654  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:11.655  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:11.655  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:11.655  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.656  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:11.656  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:11.656  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.657  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.660  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.660  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.660  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.661  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:11.661  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:11.661  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.661  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:11.668  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:33:11.668  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:11.668  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:33:11.668  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:11.668  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:11.668  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:11.668  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:11.668  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:11.668  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:11.668  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.668  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.670  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.670  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.670  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.670  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 10:33:11.670  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:11.670  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.671  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:11.673  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:33:11.673  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:33:11.673  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:33:11.673  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:33:11.673  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:33:11.673  5532  5580 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9925c88 not in the list
11-24 10:33:11.673  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.673  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
11-24 10:33:11.673  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:11.673  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.674  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:33:11.675  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.675  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.675  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:33:11.675  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:33:11.675  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:33:11.675  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:11.675  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b30621 not in the list
,11-24 10:33:11.676  5532  5580 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-24 10:33:11.676  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 10:33:11.677  5532  5580 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 10:33:11.677  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 10:33:11.677  5532  5580 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 10:33:11.677  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 10:33:11.679  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 10:33:11.679  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-24 10:33:11.680  5532  5580 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 10:33:11.680  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 10:33:11.680  5532  5580 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 10:33:11.680  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-24 10:33:11.680  5532  5580 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 10:33:11.680  5532  5580 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 10:33:11.681  5532  5580 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 10:33:11.681  5532  5580 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 10:33:11.682  5532  5580 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 10:33:11.682  5532  5580 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-24 10:33:11.683  5532  5580 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 10:33:11.683  5532  5580 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-24 10:33:11.684  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:33:11.684  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b760f6 added. We now have 3 listener(s)
11-24 10:33:11.684  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:33:11.686  5532  5580 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 10:33:11.687   932  3087 D WifiService: setWifiEnabled: true pid=5532, uid=10077
11-24 10:33:11.687   932  3087 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:33:11.729  4580  4785 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-24 10:33:11.729  4580  4790 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 10:33:11.730  5532  5585 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-24 10:33:11.730  5532  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 10:33:11.730  5532  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,11-24 10:33:12.149  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:33:13.346   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:14.347   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:15.348   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:16.349   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:16.693  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:33:16.693  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee36cf7 added. We now have 4 listener(s)
,11-24 10:33:16.693  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:33:16.706  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:16.708  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee36cf7 removed from the list
,11-24 10:33:16.708  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:33:16.711  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:33:16.711  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12d764 added. We now have 4 listener(s)
,11-24 10:33:16.711  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:33:16.714  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:16.714  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12d764 removed from the list
,11-24 10:33:16.714  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:33:16.716  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:33:16.716  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe5dcd added. We now have 4 listener(s)
11-24 10:33:16.716  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:33:16.721   932  3727 D WifiService: setWifiEnabled: false pid=5532, uid=10077
,11-24 10:33:16.721   932  3727 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:33:16.732   932  2908 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 10:33:16.732   932  2908 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 10:33:16.732   932  2908 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 10:33:16.733   932  2908 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:33:16.738  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:33:16.738  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 10:33:16.741  4580  4651 D BluetoothAdapterState: Current state: ON, message: 23
11-24 10:33:16.741  4580  4651 D BluetoothAdapterProperties: Setting state to 13
11-24 10:33:16.741  4580  4651 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 10:33:16.742  4580  4651 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 10:33:16.743  4580  4651 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:33:16.744  4580  4580 D BluetoothMapService: onReceive
11-24 10:33:16.745  4580  4580 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:33:16.745   932  5303 D DhcpClient: Clearing IP address
11-24 10:33:16.745  4580  4580 D BluetoothMapService: STATE_TURNING_OFF
11-24 10:33:16.745   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:33:16.745  4580  4580 D BluetoothMapService: MAP Service closeService in
11-24 10:33:16.745  4580  4580 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 10:33:16.746  4580  4580 D ObexServerSockets0: shutdown(block = true)
11-24 10:33:16.747  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:33:16.747  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:33:16.747  4580  4802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 10:33:16.747  4580  4580 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:33:16.749  4580  4803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 10:33:16.748  4580  4580 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:33:16.749  4580  4790 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 10:33:16.749   509   925 D CommandListener: Setting iface cfg
11-24 10:33:16.750  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:16.750  5532  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 10:33:16.750  5532  5580 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-24 10:33:16.754  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:16.755  3514  5358 V NativeCrypto: Read error: ssl=0x7f9f0b9000: I/O error during system call, Connection timed out
11-24 10:33:16.755   932  5304 D DhcpClient: Receive thread stopped
11-24 10:33:16.757  3514  5358 V NativeCrypto: SSL shutdown failed: ssl=0x7f9f0b9000: I/O error during system call, Broken pipe
,11-24 10:33:16.758  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:33:16.759   932   942 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-24 10:33:16.760   932  5301 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-24 10:33:16.761  4580  4580 I BtOppRfcommListener: stopping Accept Thread
11-24 10:33:16.761  4580  5235 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 10:33:16.761  4580  5235 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 10:33:16.762   932  5301 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-24 10:33:16.762  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:16.762   932  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-24 10:33:16.762   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:33:16.763   932  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 10:33:16.767   932   945 I ActivityManager: Start proc 5591:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 10:33:16.768  4580  4655 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:33:16.769  4580  4651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 10:33:16.769   932  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 10:33:16.769   932  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-24 10:33:16.773  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:16.773  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:33:16.774  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:16.774  5532  5532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:33:16.776   932   932 D RttService: SCAN_AVAILABLE : 1
11-24 10:33:16.776   535   535 E Parcel  : Reading a NULL string not supported here.
11-24 10:33:16.776   932  3016 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 10:33:16.776  4580  4580 D HeadsetService: Received stop request...Stopping profile...
11-24 10:33:16.777   932  2910 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-24 10:33:16.778   932  2908 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 10:33:16.779  3674  3817 W QCNEJ   : |CORE| network lost: 100
11-24 10:33:16.780  3674  3817 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 10:33:16.783  3050  3062 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:16.783   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:16.783   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:16.783  3748  3927 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:16.783   932  2908 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 10:33:16.783   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:16.786  4580  4580 D A2dpService: Received stop request...Stopping profile...
11-24 10:33:16.786  4580  4795 D A2dpStateMachine: Exit Disconnected: -1
11-24 10:33:16.787   932   932 D BluetoothA2dp: Proxy object disconnected
11-24 10:33:16.789  4580  4580 D HidService: Received stop request...Stopping profile...
11-24 10:33:16.789  4580  4580 D HidService: Stopping Bluetooth HidService
11-24 10:33:16.791  4580  4580 D HealthService: Received stop request...Stopping profile...
11-24 10:33:16.794  4580  4580 D PanService: Received stop request...Stopping profile...
11-24 10:33:16.795  4580  4580 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:16.795  4580  4580 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:16.796  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:16.796  4580  4580 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:16.797  4580  4580 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 10:33:16.798  4580  4580 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 10:33:16.798  4580  4785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:16.798  4580  4785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:16.798  4580  4785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 10:33:16.799  4580  4580 D BluetoothMapService: Received stop request...Stopping profile...
11-24 10:33:16.799  4580  4580 D BluetoothMapService: stop()
11-24 10:33:16.799  4580  4580 D BluetoothMapAppObserver: deinitObservers()
11-24 10:33:16.799  4580  4580 D BluetoothMapAppObserver: removeReceiver()
11-24 10:33:16.800  4580  4655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 10:33:16.801  4580  4655 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-24 10:33:16.806  4580  4580 D SapService: Received stop request...Stopping profile...
,11-24 10:33:16.806  4580  4580 V SapService: stop()
,11-24 10:33:16.808  3050  3050 D HeadsetProfile: Bluetooth service disconnected
,11-24 10:33:16.808  3050  3050 D BluetoothA2dp: Proxy object disconnected
11-24 10:33:16.808  3050  3050 D BluetoothInputDevice: Proxy object disconnected
11-24 10:33:16.808  3050  3050 D HidProfile: Bluetooth service disconnected
11-24 10:33:16.808  3050  3050 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 10:33:16.809  3050  3050 D PanProfile: Bluetooth service disconnected
11-24 10:33:16.809  3050  3050 D BluetoothMap: Proxy object disconnected
11-24 10:33:16.809  3050  3050 D MapProfile: Bluetooth service disconnected
11-24 10:33:16.809   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:33:16.812  4580  4580 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:33:16.812  4580  4580 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:16.812  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:16.812  4580  4580 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:33:16.813  4580  4655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 10:33:16.813  4580  4785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:16.813  4580  4580 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:16.813  4580  4580 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:16.813  4580  4785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:16.813  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:16.814  4580  4580 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:16.814  4580  4785 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 10:33:16.814  4580  4785 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-24 10:33:16.814  4580  4785 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 10:33:16.814  4580  4785 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 10:33:16.814  4580  4580 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 10:33:16.814  4580  4580 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 10:33:16.814  4580  4655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 10:33:16.814  4580  4580 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:16.814  4580  4580 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:16.814  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:16.814  4580  4580 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:16.815  4580  4580 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 10:33:16.815  4580  4655 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 10:33:16.815  4580  4580 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 10:33:16.815  4580  4580 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:33:16.815  4580  4580 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:16.815  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:16.816  4580  4580 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:16.816  4580  4580 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 10:33:16.816  4580  4580 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 10:33:16.817  4580  4580 D BluetoothMapService: MAP Service closeService in
11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isTurningOn()=false
,11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:16.817  4580  4580 D BluetoothMapService: cleanup()
11-24 10:33:16.817  4580  4580 D BluetoothMapService: MAP Service closeService in
11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:16.817  4580  4580 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:16.817  4580  4651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-24 10:33:16.817  4580  4651 D BluetoothAdapterProperties: Setting state to 15
,11-24 10:33:16.818  4580  4651 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-24 10:33:16.818  4580  4651 I BluetoothAdapterState: Entering BleOnState
,11-24 10:33:16.818   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:16.818   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:16.819  3050  3911 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 10:33:16.822  3050  3064 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:16.822  3050  3062 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:33:16.823  3050  3911 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 10:33:16.823   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:33:16.823  3050  3064 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 10:33:16.824   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 10:33:16.825  3050  3062 D BluetoothPan: onBluetoothStateChange on: false
11-24 10:33:16.826  3748  3759 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:16.827  4580  4651 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-24 10:33:16.827  4580  4651 D BluetoothAdapterProperties: Setting state to 16
11-24 10:33:16.827  4580  4651 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-24 10:33:16.827  4580  4651 D BluetoothAdapterProperties: onBleDisable
,11-24 10:33:16.828  4580  4651 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:33:16.828  4580  4652 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 10:33:16.829  4580  4655 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:33:16.829  4580  4785 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 10:33:16.829  4580  4785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:16.831  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:16.831  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:33:16.833  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:33:16.835  5591  5591 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-24 10:33:16.839   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 10:33:16.839   509   925 D CommandListener: Clearing all IP addresses on wlan0
11-24 10:33:16.840   509   925 D TetherController: Setting IP forward enable = 0
11-24 10:33:16.840   932  2910 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 10:33:16.841   932  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 10:33:16.843   932   949 D Tethering: MasterInitialState.processMessage what=3
11-24 10:33:16.848  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:16.851  5188  5188 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dee2d78 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-24 10:33:16.854  4976  5000 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 10:33:16.854  4976  5000 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 10:33:16.854  4976  5000 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 10:33:16.854  4976  5000 E SarControlService: no key has been found,reset the power
11-24 10:33:16.854  4976  5013 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 10:33:16.854  4976  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 10:33:16.854  4976  5013 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 10:33:16.855  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:33:16.855  5001  5001 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 10:33:16.852  3904  3904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 10:33:16.857  4976  5013 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 10:33:16.857  4976  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 10:33:16.857  4976  5013 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 10:33:16.857  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:33:16.858  5001  5001 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 10:33:16.860  5001  5015 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc9c51e HexData = [00000000ea03000000000000ffffffff]
11-24 10:33:16.860  5001  5015 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:33:16.860  5001  5015 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 10:33:16.861  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:33:16.861  4976  4986 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 10:33:16.864  5001  5015 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc9c51e HexData = [00000000eb03000000000000ffffffff]
11-24 10:33:16.864  5001  5015 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:33:16.864  5001  5015 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 10:33:16.865  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:33:16.866  4976  4987 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 10:33:16.875  5591  5591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 10:33:16.881   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@61b822a:true
11-24 10:33:16.881  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:33:16.898   509   925 E Netd    : netlink response contains error (No such file or directory)
11-24 10:33:16.898  5591  5591 D LocalBluetoothProfileManager: Adding local MAP profile
11-24 10:33:16.899   932  2910 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 10:33:16.900   932  2908 D DhcpClient: doQuit
11-24 10:33:16.900   932  2908 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 10:33:16.900   509   925 D TetherController: Setting IP forward enable = 0
11-24 10:33:16.900  5591  5591 D BluetoothMap: Create BluetoothMap proxy object
11-24 10:33:16.901  3372  3372 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 10:33:16.901   932  5303 D DhcpClient: onQuitting
,11-24 10:33:16.906  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:16.906  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:33:16.906  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:16.907  5532  5532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:33:16.907  5591  5591 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 10:33:16.913  5591  5591 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:33:16.914  3372  3372 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 10:33:16.916  5591  5591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 10:33:16.921  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:33:16.921  5591  5591 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:33:16.922   932  3087 I ActivityManager: Killing 5332:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 10:33:16.923  3372  3372 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 10:33:16.938  3372  3372 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 10:33:16.946  3796  3796 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 10:33:16.948  3796  3796 D SystemUpdateService: onCreate
11-24 10:33:16.949  3372  3372 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-24 10:33:16.952  3796  3796 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 10:33:16.959  3796  5629 I SystemUpdateService: active receiver: enabled
,11-24 10:33:16.960  3796  3796 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 10:33:16.966  3796  5328 I iu.UploadsManager: num queued entries: 0
,11-24 10:33:16.966  3796  5328 I iu.UploadsManager: num updated entries: 0
11-24 10:33:16.967  3796  5328 I iu.SyncManager: NEXT; no task
,11-24 10:33:16.969  3796  3796 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 10:33:16.970  3796  3796 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 10:33:16.973  3796  5629 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 10:33:16.975  3796  5629 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 10:33:16.975  3796  5629 I SystemUpdateService: now status is 0 (complete)
11-24 10:33:16.975  3796  5629 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 10:33:16.975  3796  5629 I SystemUpdateService: file has been verified
11-24 10:33:16.976  3796  5629 I SystemUpdateService: OTA package size = 21989297
,11-24 10:33:16.981  3796  5629 I SystemUpdateService: showing system update notification
11-24 10:33:16.982   932  3722 I ActivityManager: Start proc 5631:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 10:33:16.995   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 10:33:17.000  3796  3796 D SystemUpdateService: onDestroy
,11-24 10:33:17.016  5631  5631 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 10:33:17.018  5631  5631 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 10:33:17.025  5631  5631 D SprintDMHelper: simOperator: 
11-24 10:33:17.025  5631  5631 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 10:33:17.037  4940  5643 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 10:33:17.040  4580  4655 I bt_hci  : shut_down
,11-24 10:33:17.051   932  3083 I ActivityManager: Start proc 5644:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 10:33:17.053   932  3083 I ActivityManager: Killing 5188:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 10:33:17.075  4580  4659 D bt_hwcfg: hw_epilog_process
,11-24 10:33:17.078  4580  4659 I bt_vendor: low_power_mode_cb
11-24 10:33:17.078   932  2908 D wifi    : In wifi stop Hal
11-24 10:33:17.078   932  2908 D wifi    : halHandle = 0x7f88ce3080, mVM = 0x7fa530d140, mCls = 0x100a02
11-24 10:33:17.078  4940  4940 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:33:17.078   932  3371 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 10:33:17.078   932  3371 D WifiHAL : Got a signal to exit!!!
11-24 10:33:17.078   932  3371 I WifiHAL : Exit wifi_event_loop
,11-24 10:33:17.079   932  2908 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 10:33:17.079   932  2908 E WifiHAL : Event processing terminated
11-24 10:33:17.079   932  2908 D wifi    : In wifi cleaned up handler
11-24 10:33:17.079   932  2908 I WifiHAL : Internal cleanup completed
11-24 10:33:17.080  4001  4150 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:33:17.080  4580  4659 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 10:33:17.080  4580  4659 I bt_vendor: epilog_cb
11-24 10:33:17.081  4580  4659 I bt_hci  : epilog_finished_callback
11-24 10:33:17.081  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:33:17.083  4580  4655 I bt_hci_h4: hal_close
11-24 10:33:17.084  4580  4655 I bt_userial_vendor: device fd = 54 close
,11-24 10:33:17.094  5644  5644 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 10:33:17.101   932  3530 I ActivityManager: Killing 3826:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 10:33:17.101   932  3371 D wifi    : set interface wlan0 flags (DOWN)
11-24 10:33:17.102   932  2908 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 10:33:17.194  4580  4652 D bt_stack_manager: event_shut_down_stack finished.
,11-24 10:33:17.194  4580  4651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 10:33:17.196  4580  4651 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 10:33:17.196  4580  4580 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 10:33:17.197  4580  4580 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 10:33:17.197  4580  4580 D BtGatt.GattService: stop()
11-24 10:33:17.197  4580  4580 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 10:33:17.201  4580  4580 V BluetoothAdapterState: isTurningOff()=false
,11-24 10:33:17.201  4580  4580 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:17.201  4580  4580 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:17.201  4580  4580 V BluetoothAdapterState: isBleTurningOff()=true
11-24 10:33:17.201  4580  4651 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 10:33:17.201  4580  4651 D BluetoothAdapterProperties: Setting state to 10
11-24 10:33:17.201  4580  4651 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-24 10:33:17.202  4580  4651 I BluetoothAdapterState: Entering OffState
11-24 10:33:17.202   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 10:33:17.208  4580  4580 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 10:33:17.208  4580  4580 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 10:33:17.209  4580  4580 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 10:33:17.210  4580  4652 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 10:33:17.214  4580  4580 I art     : System.exit called, status: 0
,11-24 10:33:17.214  4580  4580 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 10:33:17.234   932  3530 I ActivityManager: Process com.android.bluetooth (pid 4580) has died
,11-24 10:33:17.305   932   949 D Tethering: InitialState.processMessage what=4
,11-24 10:33:17.308   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 10:33:17.350   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:18.350   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 10:33:21.753   932  3769 D WifiService: setWifiEnabled: true pid=5532, uid=10077
,11-24 10:33:21.753   932  3769 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:33:21.760   509   925 D SoftapController: Softap fwReload - Ok
,11-24 10:33:21.765   509   925 D CommandListener: Setting iface cfg
11-24 10:33:21.766   509   925 D CommandListener: Trying to bring down wlan0
,11-24 10:33:21.768   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:33:21.774   932  2908 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 10:33:22.373   932  2908 D wifi    : set interface wlan0 flags (UP)
11-24 10:33:22.378   932  2908 I WifiHAL : Initializing wifi
11-24 10:33:22.378   932  2908 I WifiHAL : Creating socket
11-24 10:33:22.381   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 10:33:22.384   932  2908 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 10:33:22.384   932  2908 D wifi    : Did set static halHandle = 0x7f88ce3080
,11-24 10:33:22.384   932  2908 D wifi    : halHandle = 0x7f88ce3080, mVM = 0x7fa530d140, mCls = 0x19da
11-24 10:33:22.385   932  2908 D wifi    : array field set
,11-24 10:33:22.385   932  2908 I WifiNative-HAL: interface[0] = wlan0
11-24 10:33:22.390   932  5660 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547756060800
,11-24 10:33:22.391   932  5660 D wifi    : waitForHalEvents called, vm = 0x7fa530d140, obj = 0x19da, env = 0x7f8624a2c0
,11-24 10:33:22.392   932  2908 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-24 10:33:22.396   932  2908 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
11-24 10:33:22.397  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:22.464  5661  5661 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 10:33:22.537  5661  5661 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 10:33:22.591  5661  5661 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-24 10:33:22.591  5661  5661 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 10:33:23.351   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:23.412   932  2908 D WifiConfigStore: Loading config and enabling all networks 
,11-24 10:33:23.413  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:23.414  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 10:33:23.414  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 10:33:23.414  5532  5532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 10:33:23.455   932  2908 D WifiConfigStore: loaded 0 passpoint configs
11-24 10:33:23.456   932  2908 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-24 10:33:23.457   932  2908 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 10:33:23.458   932  2908 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 10:33:23.459   932  2908 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-24 10:33:23.460   932  2908 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-24 10:33:23.461   932  2908 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 10:33:23.461   932  2908 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 10:33:23.461   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-24 10:33:23.462   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 10:33:23.462   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 10:33:23.462   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 10:33:23.462   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 10:33:23.467   932  2908 D WifiNative-HAL: Setting external_sim to 1
,11-24 10:33:23.467  4940  4940 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 10:33:23.468   932  2908 D wifi    : setting dfs flag to true, 0x7f883c6bc0
,11-24 10:33:23.469   932  2908 D WifiStateMachine: Setting OUI to DA-A1-19
,11-24 10:33:23.469   932  2908 D wifi    : setting scan oui 0x7f883c6bc0
11-24 10:33:23.469   932  2908 D WifiHAL : Sending mac address OUI
,11-24 10:33:23.474   932  2908 E native  : do suspend false
,11-24 10:33:23.484   932  2908 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 10:33:23.484   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 10:33:23.484   932   932 D RttService: SCAN_AVAILABLE : 3
11-24 10:33:23.485   932  3016 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 10:33:23.486   509   925 D CommandListener: Setting iface cfg
,11-24 10:33:23.491   932  2897 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 10:33:23.491   932  2897 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 10:33:23.502   932  2897 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 10:33:23.502   932  2897 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 10:33:23.511   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128465 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=21 mControllerEnergyUsed=79 }
,11-24 10:33:24.353   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:25.354   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:26.355   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:26.576  5661  5661 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:33:26.585  5661  5661 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:33:26.591  5661  5661 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:33:26.622   932  2908 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 10:33:26.624   932  2908 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 10:33:26.624   932  2908 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:33:26.635   932  2908 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 10:33:26.670   932  2908 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 10:33:26.677  5661  5661 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 10:33:26.758   932  3769 D WifiService: setWifiEnabled: false pid=5532, uid=10077
11-24 10:33:26.758   932  3769 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:33:26.763   932   932 D RttService: SCAN_AVAILABLE : 1
,11-24 10:33:26.763   932  3016 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 10:33:26.772   932  2908 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 10:33:26.773   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:33:26.782   932  2908 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 10:33:26.782  5661  5661 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 10:33:26.786  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:26.786  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:33:26.787  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:26.787  5532  5532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 10:33:26.791  5661  5661 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 10:33:26.795  5661  5661 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-24 10:33:26.802  5661  5661 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 10:33:26.806  5661  5661 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 10:33:26.908   932  2908 D wifi    : In wifi stop Hal
,11-24 10:33:26.909   932  2908 D wifi    : halHandle = 0x7f88ce3080, mVM = 0x7fa530d140, mCls = 0x19da
11-24 10:33:26.909  4940  4940 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:33:26.909   932  5660 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 10:33:26.909   932  5660 D WifiHAL : Got a signal to exit!!!
,11-24 10:33:26.909   932  5660 I WifiHAL : Exit wifi_event_loop
11-24 10:33:26.910   932  2908 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-24 10:33:26.910   932  2908 E WifiHAL : Event processing terminated
,11-24 10:33:26.911   932  2908 D wifi    : In wifi cleaned up handler
,11-24 10:33:26.911   932  2908 I WifiHAL : Internal cleanup completed
,11-24 10:33:26.913  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:33:26.915  4001  4150 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 10:33:26.950   932  5660 D wifi    : set interface wlan0 flags (DOWN)
,11-24 10:33:26.950   932  2908 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 10:33:27.155   932   949 D Tethering: InitialState.processMessage what=4
,11-24 10:33:27.160   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 10:33:27.356   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:28.356   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 10:33:31.800   932   949 I ActivityManager: Start proc 5667:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 10:33:31.888  5667  5667 D AdapterServiceConfig: Adding HeadsetService
,11-24 10:33:31.888  5667  5667 D AdapterServiceConfig: Adding A2dpService
11-24 10:33:31.889  5667  5667 D AdapterServiceConfig: Adding HidService
11-24 10:33:31.889  5667  5667 D AdapterServiceConfig: Adding HealthService
,11-24 10:33:31.889  5667  5667 D AdapterServiceConfig: Adding PanService
11-24 10:33:31.889  5667  5667 D AdapterServiceConfig: Adding GattService
11-24 10:33:31.889  5667  5667 D AdapterServiceConfig: Adding BluetoothMapService
11-24 10:33:31.889  5667  5667 D AdapterServiceConfig: Adding SapService
,11-24 10:33:31.900   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e64a271:true
,11-24 10:33:31.901  5667  5667 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 10:33:31.903  5667  5667 I bt_bluedroid: init
11-24 10:33:31.904  5667  5679 I BluetoothAdapterState: Entering OffState
,11-24 10:33:31.905  5667  5680 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 10:33:31.906  5667  5680 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 10:33:31.906  5667  5680 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 10:33:31.906  5667  5680 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 10:33:31.906  5667  5667 I bt_bluedroid: get_profile_interface socket
,11-24 10:33:31.908  5667  5683 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 10:33:31.908  5667  5667 I bt_bluedroid: get_profile_interface sdp
11-24 10:33:31.909  5667  5683 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 10:33:31.912  5667  5678 I bt_bluedroid: config_hci_snoop_log
11-24 10:33:31.913   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 10:33:31.917  5667  5679 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 10:33:31.917  5667  5679 D BluetoothAdapterProperties: Setting state to 14
11-24 10:33:31.917  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 10:33:31.918  5667  5679 D BluetoothBondStateMachine: make
,11-24 10:33:31.920  5667  5684 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 10:33:31.922  5667  5679 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:33:31.923  5667  5667 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 10:33:31.925  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:31.926  5667  5667 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 10:33:31.926  5667  5667 D BtGatt.GattService: Received start request. Starting profile...
11-24 10:33:31.926  5667  5667 D BtGatt.GattService: start()
11-24 10:33:31.926  5667  5667 I bt_bluedroid: get_profile_interface gatt
,11-24 10:33:31.927  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:31.927  5667  5667 D BtGatt.AdvertiseManager: advertise manager created
,11-24 10:33:31.932  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:31.932  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:31.932  5667  5667 V BluetoothAdapterState: isBleTurningOn()=true
11-24 10:33:31.932  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:31.932  5667  5679 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 10:33:31.934  5667  5679 I bt_bluedroid: bt_bluedroid
11-24 10:33:31.934  5667  5680 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 10:33:31.934  5667  5680 I bt_hci  : start_up
,11-24 10:33:31.938  5667  5680 I bt_vendor: alloc value 0xf40ff871
,11-24 10:33:31.939  5667  5680 I bt_vendor: init
11-24 10:33:31.939  5667  5680 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 10:33:31.939  5667  5680 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 10:33:32.049  5667  5680 D bt_hci  : start_up starting async portion
,11-24 10:33:32.049  5667  5687 I bt_hci  : event_finish_startup
11-24 10:33:32.049  5667  5687 I bt_hci_h4: hal_open
11-24 10:33:32.050  5667  5687 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 10:33:32.047  5688  5688 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:33:32.053  5667  5687 I bt_userial_vendor: device fd = 54 open
,11-24 10:33:32.067  5667  5687 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 10:33:32.069  5667  5687 D bt_hwcfg: Chipset BCM4358A3
11-24 10:33:32.069  5667  5687 D bt_hwcfg: Target name = [BCM4358A3]
,11-24 10:33:32.070  5667  5687 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 10:33:32.474  5667  5687 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 10:33:32.475  5667  5687 D bt_hwcfg: Settlement delay -- 100 ms
11-24 10:33:32.475  5667  5687 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 10:33:32.609  5667  5687 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 10:33:32.610  5667  5687 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 10:33:32.611  5667  5687 I bt_hwcfg: vendor lib fwcfg completed
,11-24 10:33:32.611  5667  5687 I bt_vendor: firmware callback
,11-24 10:33:32.611  5667  5687 I bt_hci  : firmware_config_callback
,11-24 10:33:32.620  5667  5690 I bt_btu  : btu_task pending for preload complete event
,11-24 10:33:32.620  5667  5690 I bt_btu_task: Bluetooth chip preload is complete
,11-24 10:33:32.621  5667  5690 I bt_btu  : btu_task received preload complete event
11-24 10:33:32.627  5667  5690 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 10:33:32.627  5667  5690 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 10:33:32.628  5667  5690 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-24 10:33:32.629  5667  5690 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-24 10:33:32.630  5667  5690 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 10:33:32.630  5667  5690 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 10:33:32.630  5667  5690 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 10:33:32.630  5667  5690 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 10:33:32.630  5667  5690 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 10:33:32.630  5667  5690 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 10:33:32.630  5667  5690 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 10:33:32.631  5667  5690 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 10:33:32.631  5667  5690 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 10:33:32.631  5667  5690 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 10:33:32.631  5667  5690 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 10:33:32.713  5667  5690 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf407d549
11-24 10:33:32.714  5667  5690 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf407d549 
,11-24 10:33:32.734  5667  5683 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 10:33:32.736  5667  5683 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 10:33:32.736  5667  5683 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 10:33:32.738  5667  5683 D BluetoothAdapterProperties: Name is: Nexus 6P
11-24 10:33:32.741  5667  5683 D BluetoothAdapterProperties: Scan Mode:20
,11-24 10:33:32.741  5667  5683 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 10:33:32.741  5667  5683 D bt_hci  : do_postload posting postload work item
11-24 10:33:32.741  5667  5687 I bt_hci  : event_postload
11-24 10:33:32.742  5667  5687 I bt_vendor: sco_config_cb
11-24 10:33:32.742  5667  5687 I bt_hci  : sco_config_callback postload finished.
,11-24 10:33:32.746  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:32.747  5667  5683 D bt_bte_conf: Device ID record 1 : primary
,11-24 10:33:32.747  5667  5683 D bt_bte_conf:   vendorId            = 000f
11-24 10:33:32.747  5667  5683 D bt_bte_conf:   vendorIdSource      = 0001
11-24 10:33:32.747  5667  5683 D bt_bte_conf:   product             = 1200
11-24 10:33:32.747  5667  5683 D bt_bte_conf:   version             = 1436
11-24 10:33:32.747  5667  5683 D bt_bte_conf:   clientExecutableURL = 
11-24 10:33:32.747  5667  5683 D bt_bte_conf:   serviceDescription  = 
11-24 10:33:32.747  5667  5683 D bt_bte_conf:   documentationURL    = 
11-24 10:33:32.747  5667  5683 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 10:33:32.747  5667  5680 D bt_stack_manager: event_start_up_stack finished
,11-24 10:33:32.748  5667  5679 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 10:33:32.748  5667  5679 D BluetoothAdapterProperties: Setting state to 15
11-24 10:33:32.748  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 10:33:32.749  5667  5679 I BluetoothAdapterState: Entering BleOnState
,11-24 10:33:32.749  5667  5687 I bt_vendor: low_power_mode_cb
,11-24 10:33:32.753  5667  5679 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 10:33:32.753  5667  5679 D BluetoothAdapterProperties: Setting state to 11
11-24 10:33:32.754  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 10:33:32.759  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:32.760  5667  5667 D HeadsetService: Received start request. Starting profile...
11-24 10:33:32.763  5667  5667 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 10:33:32.763  5667  5667 D HeadsetStateMachine: make
,11-24 10:33:32.766  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:32.772  5667  5679 I BluetoothAdapterState: Entering PendingCommandState
11-24 10:33:32.774  5667  5667 D HeadsetStateMachine: max_hf_connections = 1
11-24 10:33:32.774  5667  5667 I bt_bluedroid: get_profile_interface handsfree
11-24 10:33:32.774  5667  5683 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 10:33:32.774  5667  5683 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 10:33:32.777  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:32.778  5667  5667 D A2dpService: Received start request. Starting profile...
11-24 10:33:32.779  5667  5667 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-24 10:33:32.779  5667  5667 I bt_bluedroid: get_profile_interface avrcp
,11-24 10:33:32.786  5667  5667 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 10:33:32.786  5667  5667 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 10:33:32.786  5667  5667 D A2dpStateMachine: make
,11-24 10:33:32.787  5667  5667 I bt_bluedroid: get_profile_interface a2dp
,11-24 10:33:32.788  5667  5683 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 10:33:32.789  5667  5699 D A2dpStateMachine: Enter Disconnected: -2
,11-24 10:33:32.790  5667  5667 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 10:33:32.790  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:32.792  5667  5667 D HidService: Received start request. Starting profile...
11-24 10:33:32.792  5667  5667 I bt_bluedroid: get_profile_interface hidhost
11-24 10:33:32.792  5667  5667 D HidService: setHidService(): set to: null
11-24 10:33:32.792  5667  5683 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf405e56d
11-24 10:33:32.792  5591  5591 D BluetoothInputDevice: Proxy object connected
11-24 10:33:32.793  5667  5683 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 10:33:32.793  5591  5591 D HidProfile: Bluetooth service connected
11-24 10:33:32.794  5667  5667 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 10:33:32.795  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:32.795  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:33:32.795  5667  5667 D HealthService: Received start request. Starting profile...
,11-24 10:33:32.797  5667  5667 I bt_bluedroid: get_profile_interface health
11-24 10:33:32.797  5667  5667 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 10:33:32.798  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:32.799  5667  5667 D PanService: Received start request. Starting profile...
,11-24 10:33:32.799  5667  5667 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 10:33:32.799  5667  5667 I bt_bluedroid: get_profile_interface pan
11-24 10:33:32.800  5667  5683 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 10:33:32.800  5591  5591 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 10:33:32.801  5591  5591 D PanProfile: Bluetooth service connected
11-24 10:33:32.801  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:32.803  5591  5591 D BluetoothMap: Proxy object connected
,11-24 10:33:32.803  5591  5591 D MapProfile: Bluetooth service connected
11-24 10:33:32.803  5591  5591 D BluetoothMap: getConnectedDevices()
11-24 10:33:32.804  5667  5667 D BluetoothMapService: Received start request. Starting profile...
11-24 10:33:32.804  5667  5667 D BluetoothMapService: start()
11-24 10:33:32.806  5667  5667 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 10:33:32.807  5667  5667 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 10:33:32.807  5667  5667 D BluetoothMapAppObserver: createReceiver()
,11-24 10:33:32.809  5667  5667 D BluetoothMapAppObserver: initObservers()
11-24 10:33:32.809  5667  5667 D BluetoothMapAppObserver: getEnabledAccountItems()
11-24 10:33:32.815  5591  5591 D BluetoothMap: Bluetooth is Not enabled
11-24 10:33:32.816  5667  5667 V SapService: SapBinder()
11-24 10:33:32.816  5667  5667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:32.816  5667  5667 D SapService: Received start request. Starting profile...
11-24 10:33:32.816  5667  5667 V SapService: start()
,11-24 10:33:32.818  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:32.818  5667  5667 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:32.818  5667  5696 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 10:33:32.818  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:32.818  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:32.819  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:32.820  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:32.821  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:32.821  5667  5667 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:32.821  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:32.821  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:32.822  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:32.822  5667  5667 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:32.822  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:32.822  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:32.822  5667  5679 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 10:33:32.822  5667  5679 D BluetoothAdapterProperties: ScanMode =  20
11-24 10:33:32.822  5667  5679 D BluetoothAdapterProperties: State =  11
11-24 10:33:32.823  5667  5679 D BluetoothAdapterProperties: Setting state to 12
11-24 10:33:32.823  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 10:33:32.823   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:32.823   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:32.823  5667  5683 D BluetoothAdapterProperties: Scan Mode:21
11-24 10:33:32.823  5667  5683 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 10:33:32.824  5667  5679 I BluetoothAdapterState: Entering OnState
11-24 10:33:32.824  5591  5611 D BluetoothPan: onBluetoothStateChange on: true
11-24 10:33:32.824  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 10:33:32.824  3050  3064 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 10:33:32.827  3050  3050 D BluetoothMap: Proxy object connected
,11-24 10:33:32.827  3050  3050 D MapProfile: Bluetooth service connected
11-24 10:33:32.827  3050  3050 D BluetoothMap: getConnectedDevices()
11-24 10:33:32.827  3050  3062 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:32.827  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 10:33:32.829  3050  3911 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 10:33:32.829  5532  5532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:33:32.830  3050  3064 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 10:33:32.831  3050  3050 D BluetoothA2dp: Proxy object connected
,11-24 10:33:32.832  5591  5605 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 10:33:32.832   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 10:33:32.833   932   932 D BluetoothA2dp: Proxy object connected
,11-24 10:33:32.833  3050  3064 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 10:33:32.833  3050  3050 D BluetoothInputDevice: Proxy object connected
11-24 10:33:32.833  3050  3050 D HidProfile: Bluetooth service connected
11-24 10:33:32.834  5667  5667 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 10:33:32.834   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 10:33:32.834  3050  3911 D BluetoothPan: onBluetoothStateChange on: true
11-24 10:33:32.834  5667  5667 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 10:33:32.836  5667  5667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:32.836  3050  3050 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 10:33:32.836  5591  5611 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 10:33:32.836  3050  3050 D PanProfile: Bluetooth service connected
11-24 10:33:32.836  5591  5605 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 10:33:32.837  5667  5667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:32.837  3748  3927 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:32.840  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 10:33:32.840  5667  5667 D ObexServerSockets: Succeed to create listening sockets 
11-24 10:33:32.840  5667  5667 D ObexServerSockets0: startAccept()
11-24 10:33:32.840  5667  5667 D ObexServerSockets0: prepareForNewConnect()
11-24 10:33:32.840   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 10:33:32.841  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:32.841  5591  5591 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-24 10:33:32.842  5667  5667 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 10:33:32.842  5667  5667 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 10:33:32.843  5667  5667 D BluetoothMapService: onReceive
11-24 10:33:32.843  5667  5667 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:33:32.843  5667  5705 D ObexServerSockets0: Accepting socket connection...
11-24 10:33:32.843  5667  5706 D ObexServerSockets0: Accepting socket connection...
11-24 10:33:32.843  5667  5667 D BluetoothMapService: STATE_ON
11-24 10:33:32.844  5591  5591 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 10:33:32.845  5667  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:32.846  5667  5707 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 10:33:32.847  5667  5707 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 10:33:32.850  5591  5591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 10:33:32.852  5591  5591 D BluetoothA2dp: Proxy object connected
,11-24 10:33:32.856  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:33:32.858  5591  5591 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:33:32.863  5591  5591 D BluetoothPbap: Proxy object connected
,11-24 10:33:32.863  3050  3050 D BluetoothPbap: Proxy object connected
11-24 10:33:32.863  3050  3050 D PbapServerProfile: Bluetooth service connected
11-24 10:33:32.863  5591  5591 D PbapServerProfile: Bluetooth service connected
,11-24 10:33:32.868  5667  5667 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 10:33:32.868  5667  5667 D ObexServerSockets0: prepareForNewConnect()
11-24 10:33:32.871  5667  5711 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:33:32.882  5667  5715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:33:32.883  5667  5715 I BtOppRfcommListener: Accept thread started.
,11-24 10:33:32.925  3050  3911 D BluetoothHeadset: Proxy object connected
11-24 10:33:32.925  3050  3050 D HeadsetProfile: Bluetooth service connected
,11-24 10:33:32.925   932   932 D BluetoothHeadset: Proxy object connected
,11-24 10:33:32.925   932   932 D BluetoothHeadset: Proxy object connected
,11-24 10:33:32.925  3748  3759 D BluetoothHeadset: Proxy object connected
11-24 10:33:32.925   932   932 D BluetoothHeadset: Proxy object connected
,11-24 10:33:32.928  3050  3062 D BluetoothHeadset: Proxy object connected
11-24 10:33:32.928  3050  3050 D HeadsetProfile: Bluetooth service connected
,11-24 10:33:32.934   932   949 D BluetoothHeadset: Proxy object connected
,11-24 10:33:32.938  3748  3762 D BluetoothHeadset: Proxy object connected
,11-24 10:33:32.947  5591  5605 D BluetoothHeadset: Proxy object connected
,11-24 10:33:32.948  5591  5591 D HeadsetProfile: Bluetooth service connected
,11-24 10:33:34.781  3593  3793 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-24 10:33:34.781  3593  3793 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 10:33:34.809  3514  3514 I ConfigService: onCreate
,11-24 10:33:36.774  5667  5679 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 10:33:36.774  5667  5679 D BluetoothAdapterProperties: Setting state to 13
,11-24 10:33:36.775  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 10:33:36.776  5667  5679 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 10:33:36.778  5667  5679 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:33:36.783  5667  5667 D BluetoothMapService: onReceive
,11-24 10:33:36.783  5667  5667 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:33:36.783  5667  5667 D BluetoothMapService: STATE_TURNING_OFF
11-24 10:33:36.784  5667  5667 D BluetoothMapService: MAP Service closeService in
11-24 10:33:36.784  5667  5667 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 10:33:36.784  5667  5667 D ObexServerSockets0: shutdown(block = true)
11-24 10:33:36.786  5667  5705 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 10:33:36.788  5667  5667 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:33:36.789  5667  5706 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 10:33:36.790  5667  5692 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 10:33:36.790  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:36.790  5532  5532 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:33:36.791  5667  5667 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:33:36.793  5532  5532 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:33:36.793  5532  5532 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:33:36.794  5667  5683 D BluetoothAdapterProperties: Scan Mode:20
,11-24 10:33:36.794  5667  5667 I BtOppRfcommListener: stopping Accept Thread
11-24 10:33:36.794  5667  5679 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 10:33:36.796  5667  5715 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 10:33:36.796  5667  5715 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 10:33:36.795  5591  5591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 10:33:36.802  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:33:36.803  5667  5667 D HeadsetService: Received stop request...Stopping profile...
11-24 10:33:36.805  5591  5611 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:36.809  3050  3064 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:36.810   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:36.810   932   932 D BluetoothHeadset: Proxy object disconnected
,11-24 10:33:36.810  3748  3759 D BluetoothHeadset: Proxy object disconnected
,11-24 10:33:36.811  5667  5667 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:36.811  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:36.811  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 10:33:36.811  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:33:36.811   932   932 D BluetoothHeadset: Proxy object disconnected
11-24 10:33:36.812  5591  5591 D DockEventReceiver: finishStartingService: stopping service
11-24 10:33:36.813  5591  5591 D HeadsetProfile: Bluetooth service disconnected
11-24 10:33:36.815  3050  3050 D HeadsetProfile: Bluetooth service disconnected
,11-24 10:33:36.815  5667  5667 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 10:33:36.816  5667  5667 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 10:33:36.816  5667  5690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:36.816  5667  5690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 10:33:36.816  5667  5690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:36.816  5667  5667 D A2dpService: Received stop request...Stopping profile...
,11-24 10:33:36.817  5667  5683 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 10:33:36.817  5667  5699 D A2dpStateMachine: Exit Disconnected: -1
11-24 10:33:36.817  5667  5683 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 10:33:36.818   932   932 D BluetoothA2dp: Proxy object disconnected
11-24 10:33:36.818  5591  5591 D BluetoothA2dp: Proxy object disconnected
11-24 10:33:36.819  3050  3050 D BluetoothA2dp: Proxy object disconnected
11-24 10:33:36.822  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:33:36.822  5667  5667 D HidService: Received stop request...Stopping profile...
11-24 10:33:36.822  5667  5667 D HidService: Stopping Bluetooth HidService
,11-24 10:33:36.825  3050  3050 D BluetoothInputDevice: Proxy object disconnected
11-24 10:33:36.825  3050  3050 D HidProfile: Bluetooth service disconnected
11-24 10:33:36.825  5591  5591 D BluetoothInputDevice: Proxy object disconnected
11-24 10:33:36.825  5591  5591 D HidProfile: Bluetooth service disconnected
11-24 10:33:36.826  5667  5667 D HealthService: Received stop request...Stopping profile...
11-24 10:33:36.827  5667  5667 D PanService: Received stop request...Stopping profile...
11-24 10:33:36.828  3050  3050 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 10:33:36.828  3050  3050 D PanProfile: Bluetooth service disconnected
,11-24 10:33:36.828  5667  5667 D BluetoothMapService: Received stop request...Stopping profile...
11-24 10:33:36.828  5667  5667 D BluetoothMapService: stop()
11-24 10:33:36.829  5667  5667 D BluetoothMapAppObserver: deinitObservers()
11-24 10:33:36.829  5667  5667 D BluetoothMapAppObserver: removeReceiver()
11-24 10:33:36.830  3050  3050 D BluetoothMap: Proxy object disconnected
11-24 10:33:36.830  3050  3050 D MapProfile: Bluetooth service disconnected
11-24 10:33:36.830  5591  5591 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 10:33:36.830  5591  5591 D PanProfile: Bluetooth service disconnected
11-24 10:33:36.830  5591  5591 D BluetoothMap: Proxy object disconnected
11-24 10:33:36.831  5591  5591 D MapProfile: Bluetooth service disconnected
11-24 10:33:36.831  5667  5667 D SapService: Received stop request...Stopping profile...
,11-24 10:33:36.831  5667  5667 V SapService: stop()
,11-24 10:33:36.833  5667  5667 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:36.833  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:36.833  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:36.833  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:33:36.835  5667  5690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:36.835  5667  5690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:36.835  5667  5683 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 10:33:36.835  5667  5690 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 10:33:36.835  5667  5690 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 10:33:36.835  5667  5690 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 10:33:36.835  5667  5690 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-24 10:33:36.837  5667  5667 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:36.837  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:36.837  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:36.837  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:36.837  5667  5667 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-24 10:33:36.837  5667  5667 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 10:33:36.837  5667  5683 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 10:33:36.837  5667  5667 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:36.838  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:36.838  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:36.838  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:36.838  3050  3050 D BluetoothPbap: Proxy object disconnected
11-24 10:33:36.838  3050  3050 D PbapServerProfile: Bluetooth service disconnected
11-24 10:33:36.838  5667  5667 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 10:33:36.838  5667  5683 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 10:33:36.839  5667  5667 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 10:33:36.839  5667  5667 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:33:36.839  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:36.839  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:36.839  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:36.839  5667  5667 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 10:33:36.840  5667  5667 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 10:33:36.842  5667  5667 D BluetoothMapService: MAP Service closeService in
11-24 10:33:36.842  5667  5667 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:36.842  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:36.842  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:36.842  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:33:36.842  5667  5667 D BluetoothMapService: cleanup()
11-24 10:33:36.843  5667  5667 D BluetoothMapService: MAP Service closeService in
11-24 10:33:36.843  5667  5667 V BluetoothAdapterState: isTurningOff()=true
11-24 10:33:36.843  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:36.843  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:36.843  5667  5667 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:36.843  5667  5679 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 10:33:36.843  5667  5679 D BluetoothAdapterProperties: Setting state to 15
11-24 10:33:36.843  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 10:33:36.844   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:36.844   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:36.844  5667  5679 I BluetoothAdapterState: Entering BleOnState
,11-24 10:33:36.844  5591  5605 D BluetoothPan: onBluetoothStateChange on: false
11-24 10:33:36.846  5591  5611 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:33:36.847  3050  3911 D BluetoothMap: onBluetoothStateChange: up=false
11-24 10:33:36.847  3050  3062 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:36.847  3050  3064 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:33:36.848  3050  3911 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 10:33:36.848  5591  5605 D BluetoothMap: onBluetoothStateChange: up=false
11-24 10:33:36.849   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:33:36.849  3050  3062 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 10:33:36.850   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:36.850  3050  3064 D BluetoothPan: onBluetoothStateChange on: false
11-24 10:33:36.850  5591  5611 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 10:33:36.851  5591  5605 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 10:33:36.851  5591  5611 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:33:36.852  3748  3762 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 10:33:36.852  5667  5679 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 10:33:36.852  5667  5679 D BluetoothAdapterProperties: Setting state to 16
11-24 10:33:36.852  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 10:33:36.853  5591  5591 D BluetoothPbap: Proxy object disconnected
11-24 10:33:36.853  5591  5591 D PbapServerProfile: Bluetooth service disconnected
11-24 10:33:36.853  5667  5679 D BluetoothAdapterProperties: onBleDisable
11-24 10:33:36.853  5667  5679 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:33:36.853  5667  5680 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 10:33:36.854  5667  5690 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 10:33:36.854  5667  5690 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:33:36.855  5591  5591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 10:33:36.856  5667  5683 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:33:36.858  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:33:36.859  5532  5532 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:33:36.860  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:33:36.871  5591  5591 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:33:37.065  5667  5683 I bt_hci  : shut_down
,11-24 10:33:37.070  5667  5687 D bt_hwcfg: hw_epilog_process
,11-24 10:33:37.071  5667  5687 I bt_vendor: low_power_mode_cb
,11-24 10:33:37.074  5667  5687 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 10:33:37.074  5667  5687 I bt_vendor: epilog_cb
11-24 10:33:37.074  5667  5687 I bt_hci  : epilog_finished_callback
,11-24 10:33:37.077  5667  5683 I bt_hci_h4: hal_close
,11-24 10:33:37.078  5667  5683 I bt_userial_vendor: device fd = 54 close
,11-24 10:33:37.197  5667  5680 D bt_stack_manager: event_shut_down_stack finished.
,11-24 10:33:37.197  5667  5679 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 10:33:37.201  5667  5679 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 10:33:37.201  5667  5667 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 10:33:37.202  5667  5667 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 10:33:37.202  5667  5667 D BtGatt.GattService: stop()
11-24 10:33:37.203  5667  5667 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 10:33:37.205  5667  5667 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:37.205  5667  5667 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:37.205  5667  5667 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:37.205  5667  5667 V BluetoothAdapterState: isBleTurningOff()=true
11-24 10:33:37.206  5667  5679 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 10:33:37.206  5667  5679 D BluetoothAdapterProperties: Setting state to 10
11-24 10:33:37.206  5667  5679 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 10:33:37.207  5667  5679 I BluetoothAdapterState: Entering OffState
,11-24 10:33:37.208   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 10:33:37.220  5667  5667 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 10:33:37.220  5667  5667 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 10:33:37.220  5667  5667 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 10:33:37.223  5667  5680 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 10:33:37.228  5667  5667 I art     : System.exit called, status: 0
,11-24 10:33:37.228  5667  5667 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 10:33:37.250   932  3083 I ActivityManager: Process com.android.bluetooth (pid 5667) has died
,11-24 10:33:38.357   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:39.358   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:39.835  3514  3514 I ConfigService: onDestroy,
,11-24 10:33:40.359   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:41.360   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:41.773  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:33:41.773  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 10:33:41.781  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:41.781  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe5dcd removed from the list
11-24 10:33:41.781  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:33:41.784  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:33:41.785  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d805d0 added. We now have 4 listener(s)
,11-24 10:33:41.785  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:33:41.787  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:33:41.787  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d805d0 removed from the list
,11-24 10:33:41.788  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:33:41.792  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:33:41.793  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a009c9 added. We now have 4 listener(s)
11-24 10:33:41.793  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:33:42.361   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:43.362   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 10:33:46.804  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:46.836   932   949 I ActivityManager: Start proc 5724:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 10:33:46.926  5724  5724 D AdapterServiceConfig: Adding HeadsetService
,11-24 10:33:46.926  5724  5724 D AdapterServiceConfig: Adding A2dpService
11-24 10:33:46.926  5724  5724 D AdapterServiceConfig: Adding HidService
11-24 10:33:46.927  5724  5724 D AdapterServiceConfig: Adding HealthService
11-24 10:33:46.927  5724  5724 D AdapterServiceConfig: Adding PanService
11-24 10:33:46.927  5724  5724 D AdapterServiceConfig: Adding GattService
11-24 10:33:46.927  5724  5724 D AdapterServiceConfig: Adding BluetoothMapService
11-24 10:33:46.927  5724  5724 D AdapterServiceConfig: Adding SapService
,11-24 10:33:46.937   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c372a2:true
,11-24 10:33:46.938  5724  5724 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 10:33:46.941  5724  5724 I bt_bluedroid: init
,11-24 10:33:46.941  5724  5736 I BluetoothAdapterState: Entering OffState
,11-24 10:33:46.944  5724  5737 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 10:33:46.944  5724  5737 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 10:33:46.944  5724  5737 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 10:33:46.944  5724  5737 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 10:33:46.945  5724  5724 I bt_bluedroid: get_profile_interface socket
,11-24 10:33:46.947  5724  5740 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 10:33:46.947  5724  5724 I bt_bluedroid: get_profile_interface sdp
11-24 10:33:46.948  5724  5740 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 10:33:46.953  5724  5735 I bt_bluedroid: config_hci_snoop_log
,11-24 10:33:46.954   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 10:33:46.958  5724  5736 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 10:33:46.958  5724  5736 D BluetoothAdapterProperties: Setting state to 14
11-24 10:33:46.958  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 10:33:46.960  5724  5736 D BluetoothBondStateMachine: make
,11-24 10:33:46.962  5724  5741 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 10:33:46.964  5724  5736 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:33:46.966  5724  5724 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 10:33:46.968  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:46.968  5724  5724 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 10:33:46.969  5724  5724 D BtGatt.GattService: Received start request. Starting profile...
11-24 10:33:46.969  5724  5724 D BtGatt.GattService: start()
11-24 10:33:46.969  5724  5724 I bt_bluedroid: get_profile_interface gatt
11-24 10:33:46.970  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:46.970  5724  5724 D BtGatt.AdvertiseManager: advertise manager created
,11-24 10:33:46.975  5724  5724 V BluetoothAdapterState: isTurningOff()=false
,11-24 10:33:46.975  5724  5724 V BluetoothAdapterState: isTurningOn()=false
11-24 10:33:46.975  5724  5724 V BluetoothAdapterState: isBleTurningOn()=true
11-24 10:33:46.975  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:46.976  5724  5736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 10:33:46.978  5724  5736 I bt_bluedroid: bt_bluedroid
,11-24 10:33:46.978  5724  5737 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 10:33:46.978  5724  5737 I bt_hci  : start_up
,11-24 10:33:46.984  5724  5737 I bt_vendor: alloc value 0xf40ff871
,11-24 10:33:46.984  5724  5737 I bt_vendor: init
11-24 10:33:46.984  5724  5737 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 10:33:46.984  5724  5737 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 10:33:47.093  5724  5737 D bt_hci  : start_up starting async portion
,11-24 10:33:47.093  5724  5744 I bt_hci  : event_finish_startup
11-24 10:33:47.093  5724  5744 I bt_hci_h4: hal_open
,11-24 10:33:47.093  5724  5744 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 10:33:47.097  5724  5744 I bt_userial_vendor: device fd = 54 open
11-24 10:33:47.090  5745  5745 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:33:47.112  5724  5744 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 10:33:47.115  5724  5744 D bt_hwcfg: Chipset BCM4358A3
,11-24 10:33:47.115  5724  5744 D bt_hwcfg: Target name = [BCM4358A3]
11-24 10:33:47.115  5724  5744 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 10:33:47.633  5724  5744 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-24 10:33:47.633  5724  5744 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 10:33:47.633  5724  5744 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 10:33:47.767  5724  5744 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 10:33:47.768  5724  5744 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-24 10:33:47.769  5724  5744 I bt_hwcfg: vendor lib fwcfg completed
11-24 10:33:47.770  5724  5744 I bt_vendor: firmware callback
11-24 10:33:47.770  5724  5744 I bt_hci  : firmware_config_callback
,11-24 10:33:47.778  5724  5747 I bt_btu  : btu_task pending for preload complete event
11-24 10:33:47.778  5724  5747 I bt_btu_task: Bluetooth chip preload is complete
11-24 10:33:47.779  5724  5747 I bt_btu  : btu_task received preload complete event,
,11-24 10:33:47.787  5724  5747 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 10:33:47.787  5724  5747 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 10:33:47.787  5724  5747 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 10:33:47.787  5724  5747 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-24 10:33:47.787  5724  5747 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 10:33:47.787  5724  5747 I         : BTE_InitTraceLevels -- TRC_A2D
,11-24 10:33:47.787  5724  5747 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 10:33:47.788  5724  5747 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 10:33:47.884  5724  5747 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf407d549
,11-24 10:33:47.885  5724  5747 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf407d549 
,11-24 10:33:47.901  5724  5740 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 10:33:47.903  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 10:33:47.904  5724  5740 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 10:33:47.908  5724  5740 D BluetoothAdapterProperties: Name is: Nexus 6P
11-24 10:33:47.910  5724  5740 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:33:47.911  5724  5740 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 10:33:47.911  5724  5740 D bt_hci  : do_postload posting postload work item
11-24 10:33:47.911  5724  5744 I bt_hci  : event_postload
11-24 10:33:47.911  5724  5744 I bt_vendor: sco_config_cb
,11-24 10:33:47.911  5724  5744 I bt_hci  : sco_config_callback postload finished.
11-24 10:33:47.913  5724  5740 D bt_bte_conf: Device ID record 1 : primary
,11-24 10:33:47.913  5724  5740 D bt_bte_conf:   vendorId            = 000f
11-24 10:33:47.914  5724  5740 D bt_bte_conf:   vendorIdSource      = 0001
,11-24 10:33:47.914  5724  5740 D bt_bte_conf:   product             = 1200
11-24 10:33:47.914  5724  5740 D bt_bte_conf:   version             = 1436
11-24 10:33:47.914  5724  5740 D bt_bte_conf:   clientExecutableURL = 
11-24 10:33:47.914  5724  5740 D bt_bte_conf:   serviceDescription  = 
11-24 10:33:47.914  5724  5740 D bt_bte_conf:   documentationURL    = 
,11-24 10:33:47.914  5724  5740 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 10:33:47.915  5724  5737 D bt_stack_manager: event_start_up_stack finished
,11-24 10:33:47.916  5724  5736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 10:33:47.916  5724  5736 D BluetoothAdapterProperties: Setting state to 15
,11-24 10:33:47.916  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 10:33:47.918  5724  5736 I BluetoothAdapterState: Entering BleOnState
11-24 10:33:47.922  5724  5744 I bt_vendor: low_power_mode_cb
,11-24 10:33:47.925  5724  5736 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 10:33:47.925  5724  5736 D BluetoothAdapterProperties: Setting state to 11
11-24 10:33:47.925  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 10:33:47.936  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:47.944  5724  5724 D HeadsetService: Received start request. Starting profile...
11-24 10:33:47.946  5724  5736 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:33:47.947  5724  5724 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 10:33:47.947  5724  5724 D HeadsetStateMachine: make
,11-24 10:33:47.956  5724  5724 D HeadsetStateMachine: max_hf_connections = 1
,11-24 10:33:47.956  5724  5724 I bt_bluedroid: get_profile_interface handsfree
11-24 10:33:47.957  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 10:33:47.957  5724  5740 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 10:33:47.960  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:47.961  5724  5724 D A2dpService: Received start request. Starting profile...
,11-24 10:33:47.961  5724  5724 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 10:33:47.962  5724  5724 I bt_bluedroid: get_profile_interface avrcp
,11-24 10:33:47.968  5724  5724 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 10:33:47.968  5724  5724 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 10:33:47.968  5724  5724 D A2dpStateMachine: make
,11-24 10:33:47.970  5724  5724 I bt_bluedroid: get_profile_interface a2dp
,11-24 10:33:47.971  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 10:33:47.972  5724  5756 D A2dpStateMachine: Enter Disconnected: -2
11-24 10:33:47.973  5724  5724 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 10:33:47.974  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:47.975  5724  5724 D HidService: Received start request. Starting profile...
11-24 10:33:47.975  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:33:47.975  5724  5724 I bt_bluedroid: get_profile_interface hidhost
11-24 10:33:47.975  5724  5724 D HidService: setHidService(): set to: null
11-24 10:33:47.975  5724  5740 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf405e56d
11-24 10:33:47.975  5724  5740 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-24 10:33:47.976  5724  5724 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 10:33:47.976  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:33:47.977  5724  5724 D HealthService: Received start request. Starting profile...
,11-24 10:33:47.979  5724  5724 I bt_bluedroid: get_profile_interface health
,11-24 10:33:47.979  5724  5724 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 10:33:47.980  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:47.980  5724  5724 D PanService: Received start request. Starting profile...
11-24 10:33:47.981  5724  5724 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-24 10:33:47.981  5724  5724 I bt_bluedroid: get_profile_interface pan
11-24 10:33:47.981  5724  5740 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 10:33:47.983  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:47.983  5724  5724 D BluetoothMapService: Received start request. Starting profile...
11-24 10:33:47.983  5724  5724 D BluetoothMapService: start()
,11-24 10:33:47.990  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 10:33:47.990  5724  5724 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 10:33:47.990  5724  5724 D BluetoothMapAppObserver: createReceiver()
11-24 10:33:47.992  5724  5724 D BluetoothMapAppObserver: initObservers()
11-24 10:33:47.992  5724  5724 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 10:33:47.999  5724  5724 V SapService: SapBinder()
11-24 10:33:47.999  5724  5724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
11-24 10:33:48.000  5724  5724 D SapService: Received start request. Starting profile...
,11-24 10:33:48.000  5724  5724 V SapService: start()
,11-24 10:33:48.003  5724  5724 V BluetoothAdapterState: isTurningOff()=false
,11-24 10:33:48.003  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:48.003  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:48.003  5724  5754 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 10:33:48.003  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:48.004  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:33:48.005  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:48.005  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:48.005  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:48.005  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:48.006  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:33:48.007  5724  5724 V BluetoothAdapterState: isTurningOff()=false
11-24 10:33:48.007  5724  5724 V BluetoothAdapterState: isTurningOn()=true
11-24 10:33:48.007  5724  5724 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:33:48.007  5724  5724 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:33:48.007  5724  5736 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 10:33:48.008  5724  5736 D BluetoothAdapterProperties: ScanMode =  20
11-24 10:33:48.008  5724  5736 D BluetoothAdapterProperties: State =  11
11-24 10:33:48.008  5724  5736 D BluetoothAdapterProperties: Setting state to 12
11-24 10:33:48.008  5724  5736 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-24 10:33:48.008  5724  5736 I BluetoothAdapterState: Entering OnState
11-24 10:33:48.009   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:48.009   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:48.009  5724  5740 D BluetoothAdapterProperties: Scan Mode:21
11-24 10:33:48.009  5724  5740 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 10:33:48.009  5591  5611 D BluetoothPan: onBluetoothStateChange on: true
11-24 10:33:48.011  5591  5605 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 10:33:48.013  3050  3062 D BluetoothMap: onBluetoothStateChange: up=true
11-24 10:33:48.015  3050  3911 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:48.016  3050  3911 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 10:33:48.016  3050  3050 D BluetoothMap: Proxy object connected
,11-24 10:33:48.016  3050  3050 D MapProfile: Bluetooth service connected
11-24 10:33:48.016  3050  3050 D BluetoothMap: getConnectedDevices()
11-24 10:33:48.012  5591  5591 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 10:33:48.016  5591  5591 D PanProfile: Bluetooth service connected
11-24 10:33:48.017  5591  5591 D BluetoothA2dp: Proxy object connected
11-24 10:33:48.017  3050  3064 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 10:33:48.018  3050  3050 D BluetoothA2dp: Proxy object connected
11-24 10:33:48.019  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 10:33:48.019  5724  5724 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-24 10:33:48.019  5591  5605 D BluetoothMap: onBluetoothStateChange: up=true
11-24 10:33:48.021  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:48.021  5591  5591 D BluetoothMap: Proxy object connected
11-24 10:33:48.021  5591  5591 D MapProfile: Bluetooth service connected
11-24 10:33:48.021  5591  5591 D BluetoothMap: getConnectedDevices()
11-24 10:33:48.022   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 10:33:48.023  3050  3911 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 10:33:48.023   932   932 D BluetoothA2dp: Proxy object connected
11-24 10:33:48.023  5724  5724 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:48.025  5724  5724 D ObexServerSockets: Succeed to create listening sockets 
,11-24 10:33:48.025   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:48.025  5724  5724 D ObexServerSockets0: startAccept()
11-24 10:33:48.025  5724  5724 D ObexServerSockets0: prepareForNewConnect()
11-24 10:33:48.025  3050  3062 D BluetoothPan: onBluetoothStateChange on: true
11-24 10:33:48.026  5724  5724 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 10:33:48.027  5724  5724 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 10:33:48.027  5591  5761 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 10:33:48.027  3050  3050 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 10:33:48.027  3050  3050 D PanProfile: Bluetooth service connected
11-24 10:33:48.028  3050  3050 D BluetoothInputDevice: Proxy object connected
,11-24 10:33:48.028  3050  3050 D HidProfile: Bluetooth service connected
,11-24 10:33:48.028  5724  5762 D ObexServerSockets0: Accepting socket connection...
11-24 10:33:48.028  5724  5763 D ObexServerSockets0: Accepting socket connection...
11-24 10:33:48.029  5591  5591 D BluetoothInputDevice: Proxy object connected
11-24 10:33:48.030  5591  5591 D HidProfile: Bluetooth service connected
11-24 10:33:48.032  5591  5605 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 10:33:48.035  5591  5611 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:48.036  3748  3762 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:33:48.038   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 10:33:48.038  5724  5724 D BluetoothMapService: onReceive
11-24 10:33:48.038  5724  5724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:33:48.038  5724  5724 D BluetoothMapService: STATE_ON
11-24 10:33:48.042  5724  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:33:48.043  5591  5591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 10:33:48.045  5724  5764 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 10:33:48.045  5724  5764 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 10:33:48.050  3514  3514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:33:48.050  5591  5591 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:33:48.058  5591  5591 D BluetoothPbap: Proxy object connected
,11-24 10:33:48.058  5591  5591 D PbapServerProfile: Bluetooth service connected
,11-24 10:33:48.063  5724  5724 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 10:33:48.064  5724  5724 D ObexServerSockets0: prepareForNewConnect()
11-24 10:33:48.066  5724  5769 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:33:48.071  3050  3050 D BluetoothPbap: Proxy object connected
,11-24 10:33:48.072  3050  3050 D PbapServerProfile: Bluetooth service connected
,11-24 10:33:48.082  5724  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:33:48.084  5724  5773 I BtOppRfcommListener: Accept thread started.
,11-24 10:33:48.111  5591  5605 D BluetoothHeadset: Proxy object connected
,11-24 10:33:48.111  3050  3911 D BluetoothHeadset: Proxy object connected
11-24 10:33:48.111  3050  3050 D HeadsetProfile: Bluetooth service connected
11-24 10:33:48.111   932   932 D BluetoothHeadset: Proxy object connected
11-24 10:33:48.112   932   932 D BluetoothHeadset: Proxy object connected
11-24 10:33:48.112  3748  4151 D BluetoothHeadset: Proxy object connected
11-24 10:33:48.112   932   932 D BluetoothHeadset: Proxy object connected
,11-24 10:33:48.113  5591  5591 D HeadsetProfile: Bluetooth service connected
,11-24 10:33:48.116  3050  3062 D BluetoothHeadset: Proxy object connected
,11-24 10:33:48.116  3050  3050 D HeadsetProfile: Bluetooth service connected
,11-24 10:33:48.125   932   949 D BluetoothHeadset: Proxy object connected
,11-24 10:33:48.136  5591  5611 D BluetoothHeadset: Proxy object connected
,11-24 10:33:48.137  3748  3927 D BluetoothHeadset: Proxy object connected
11-24 10:33:48.137  5591  5591 D HeadsetProfile: Bluetooth service connected
,11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:33:51.821  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 10:33:51.827  5532  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 10:33:51.828  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:33:51.828  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a009c9 removed from the list
11-24 10:33:51.828  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:33:51.830  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:33:51.831  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19598ce added. We now have 4 listener(s)
11-24 10:33:51.831  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:33:51.835   932  3743 D WifiService: setWifiEnabled: false pid=5532, uid=10077
,11-24 10:33:51.835   932  3743 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:33:51.841  4001  4401 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-24 10:33:56.846  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:33:56.847   932  3727 D WifiService: setWifiEnabled: true pid=5532, uid=10077
11-24 10:33:56.848   932  3727 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:33:56.860   509   925 D SoftapController: Softap fwReload - Ok
,11-24 10:33:56.864   509   925 D CommandListener: Setting iface cfg
,11-24 10:33:56.864   509   925 D CommandListener: Trying to bring down wlan0
11-24 10:33:56.865   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:33:56.871   932  2908 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 10:33:57.554   932  2908 D wifi    : set interface wlan0 flags (UP)
,11-24 10:33:57.558   932  2908 I WifiHAL : Initializing wifi
11-24 10:33:57.559   932  2908 I WifiHAL : Creating socket
,11-24 10:33:57.563   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 10:33:57.568   932  2908 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 10:33:57.568   932  2908 D wifi    : Did set static halHandle = 0x7f88ce3080
11-24 10:33:57.568   932  2908 D wifi    : halHandle = 0x7f88ce3080, mVM = 0x7fa530d140, mCls = 0x198a
11-24 10:33:57.568   932  2908 D wifi    : array field set
11-24 10:33:57.568   932  2908 I WifiNative-HAL: interface[0] = wlan0
,11-24 10:33:57.571   932  5779 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547756060800
11-24 10:33:57.571   932  5779 D wifi    : waitForHalEvents called, vm = 0x7fa530d140, obj = 0x198a, env = 0x7f862499c0
,11-24 10:33:57.616  5780  5780 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 10:33:57.672   932  2908 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 10:33:57.697  5780  5780 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 10:33:57.780  5780  5780 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-24 10:33:57.780  5780  5780 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 10:33:57.821   932  2908 D WifiConfigStore: Loading config and enabling all networks 
,11-24 10:33:57.851   932  2908 D WifiConfigStore: loaded 0 passpoint configs
,11-24 10:33:57.852   932  2908 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 10:33:57.853   932  2908 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-24 10:33:57.854   932  2908 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 10:33:57.854   932  2908 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 10:33:57.855   932  2908 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-24 10:33:57.856   932  2908 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 10:33:57.857   932  2908 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-24 10:33:57.857   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 10:33:57.857   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 10:33:57.857   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 10:33:57.857   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 10:33:57.857   932  2908 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 10:33:57.862   932  2908 D WifiNative-HAL: Setting external_sim to 1
,11-24 10:33:57.863   932  2908 D wifi    : setting dfs flag to true, 0x7f883c6780
,11-24 10:33:57.864   932  2908 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 10:33:57.864   932  2908 D wifi    : setting scan oui 0x7f883c6780
11-24 10:33:57.864   932  2908 D WifiHAL : Sending mac address OUI
11-24 10:33:57.865  4940  4940 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 10:33:57.868   932  2908 E native  : do suspend false
,11-24 10:33:57.881   932  2908 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 10:33:57.881   932   932 D RttService: SCAN_AVAILABLE : 3
,11-24 10:33:57.881   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 10:33:57.881   932  3016 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 10:33:57.882   509   925 D CommandListener: Setting iface cfg
,11-24 10:33:57.888   932  2897 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '137 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 137 Failed to set address (No such device)'
,11-24 10:33:57.888   932  2897 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 10:33:57.897   932  2897 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 10:33:57.903   932  2897 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 10:33:57.903   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=162858 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-24 10:33:58.363   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:33:59.364   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:00.365   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:00.995   932  2908 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 10:34:00.997   932  2908 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 10:34:00.998   932  2908 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:34:01.010   932  2908 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 10:34:01.045   932  2908 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 10:34:01.051  5780  5780 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 10:34:01.366   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:01.472  5780  5780 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 10:34:01.505  5780  5780 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 10:34:01.507  5780  5780 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 10:34:01.514   932  2908 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 10:34:01.514   932  2908 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 10:34:01.514   932  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 10:34:01.531   932  2908 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:34:01.545   509   925 D CommandListener: Setting iface cfg
,11-24 10:34:01.551   932  2908 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 10:34:01.557   932  5785 D DhcpClient: Receive thread started
,11-24 10:34:01.562   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:34:01.562   932  2908 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 10:34:01.563   932  2910 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 10:34:01.643   932  2908 E native  : do suspend false
,11-24 10:34:01.655   932  5784 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 10:34:01.670   932  5785 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172674, domain null
,11-24 10:34:01.670   932  5784 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172674 seconds
,11-24 10:34:01.672   932  5784 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 10:34:01.684   932  5785 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 10:34:01.685   932  5784 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 10:34:01.691   509   925 D CommandListener: Setting iface cfg
,11-24 10:34:01.696   932  2908 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 10:34:01.701   932  5784 D DhcpClient: Scheduling renewal in 86399s
,11-24 10:34:01.711   932  2908 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 10:34:01.713   932  2908 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 10:34:01.714   932  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 10:34:01.724   932  2910 D ConnectivityService: Adding iface wlan0 to network 101
,11-24 10:34:01.723   932  2908 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 10:34:01.773   932  2910 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 10:34:01.773   932  2910 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 10:34:01.775   932  2910 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 10:34:01.777   932  2910 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 10:34:01.778   932  2910 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 10:34:01.786   932  2910 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:34:01.791   932  2910 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 10:34:01.791   932  2910 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 10:34:01.792   932  2910 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 10:34:01.792   932  2910 D ConnectivityService:    accepting network in place of null
11-24 10:34:01.793   932  2910 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-24 10:34:01.793   932  2908 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 10:34:01.793   932  2908 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 10:34:01.804   932  5783 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166758, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 10:34:01.817   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:34:01.837   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:34:01.840   932  2910 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 10:34:01.840   932  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 10:34:01.841  3674  3817 W QCNEJ   : |CORE| network available: 101
11-24 10:34:01.841   932  2910 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 10:34:01.843   932   949 D Tethering: MasterInitialState.processMessage what=3
11-24 10:34:01.844  3674  3817 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 10:34:01.845  3674  3817 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 10:34:01.845  3674  3817 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 10:34:01.857  4976  5000 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 10:34:01.857  4976  5000 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 10:34:01.857  4976  5000 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 10:34:01.857  4976  5000 E SarControlService: no key has been found,reset the power
11-24 10:34:01.858  4976  5013 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 10:34:01.858  4976  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 10:34:01.858  4976  5013 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-24 10:34:01.858  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:34:01.858  5001  5001 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 10:34:01.860  3904  3904 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 10:34:01.861  4976  5013 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 10:34:01.861  4976  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 10:34:01.861  4976  5013 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 10:34:01.862  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:34:01.862  5001  5001 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 10:34:01.864  3796  3796 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 10:34:01.865  5001  5015 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc9c51e HexData = [00000000ec03000000000000ffffffff]
11-24 10:34:01.865  5001  5015 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 10:34:01.865  5001  5015 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 10:34:01.865  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:34:01.866  4976  4986 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 10:34:01.866  5001  5015 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@cc9c51e HexData = [00000000ed03000000000000ffffffff]
11-24 10:34:01.866  5001  5015 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:34:01.866  5001  5015 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 10:34:01.867  5001  5001 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:34:01.867  4976  4987 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 10:34:01.871  3796  3796 D SystemUpdateService: onCreate
,11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:34:01.874  5532  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:34:01.875  3796  3796 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 10:34:01.876  5532  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 10:34:01.876  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:01.876  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19598ce removed from the list
11-24 10:34:01.876  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:34:01.879  5532  5580 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-24 10:34:01.880  5532  5580 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-24 10:34:01.882  5532  5580 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@63b1f82 Bundle[{}]
11-24 10:34:01.882  5532  5580 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 10:34:01.883  5532  5580 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 10:34:01.883  5532  5580 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 10:34:01.884  5532  5580 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 10:34:01.884  5532  5580 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 10:34:01.885  5532  5580 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-24 10:34:01.885  3796  5798 I SystemUpdateService: active receiver: enabled
,11-24 10:34:01.892  5532  5580 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-24 10:34:01.893  5532  5580 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-24 10:34:01.893  5532  5580 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-24 10:34:01.895  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:34:01.895  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9503ef added. We now have 3 listener(s)
,11-24 10:34:01.895  3796  3796 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 10:34:01.896  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:01.896  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:01.897  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:01.897  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:01.897  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67faefc added. We now have 4 listener(s)
11-24 10:34:01.897  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:34:01.898  3796  5328 I iu.UploadsManager: num queued entries: 0
,11-24 10:34:01.898  3796  5328 I iu.UploadsManager: num updated entries: 0
,11-24 10:34:01.900  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 10:34:01.901  3796  5798 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-24 10:34:01.902  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:34:01.902  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e967985 added. We now have 4 listener(s)
11-24 10:34:01.903  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:01.904  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:01.904  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:01.904  3796  5328 I iu.SyncManager: NEXT; no task
11-24 10:34:01.904  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:01.904  3796  5798 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 10:34:01.904  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f673da added. We now have 5 listener(s)
11-24 10:34:01.904  3796  5798 I SystemUpdateService: now status is 0 (complete)
11-24 10:34:01.904  3796  5798 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 10:34:01.904  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:01.904  3796  5798 I SystemUpdateService: file has been verified
11-24 10:34:01.904  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:34:01.904  3796  5798 I SystemUpdateService: OTA package size = 21989297
11-24 10:34:01.904  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:34:01.904  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:34:01.905  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:01.905  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:01.905  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:01.905  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9503ef removed from the list
11-24 10:34:01.905  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:01.905  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67faefc removed from the list
11-24 10:34:01.905  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:34:01.905  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.905  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.907  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.907  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.907  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.907  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:01.907  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:01.907  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:34:01.907  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67faefc not in the list
11-24 10:34:01.907  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.907  3796  3796 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 10:34:01.907  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.909  3796  3796 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 10:34:01.909  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.909  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.909  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.909  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:01.909  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:01.909  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:01.909  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f673da removed from the list
,11-24 10:34:01.909  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:01.909  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:01.909  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:01.909  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e967985 removed from the list
11-24 10:34:01.910  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:34:01.910  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d7f00b added. We now have 3 listener(s)
11-24 10:34:01.911  5631  5631 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 10:34:01.912  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:01.912  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 10:34:01.912  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:01.913  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:01.913  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96bee8 added. We now have 4 listener(s)
11-24 10:34:01.913  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:01.914  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:34:01.914  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:34:01.915  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ca2901 added. We now have 4 listener(s)
11-24 10:34:01.916  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:01.916  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:01.916  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 10:34:01.916  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:01.916  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d57f3a6 added. We now have 5 listener(s)
11-24 10:34:01.916  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:01.916  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:34:01.916  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:34:01.916  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:34:01.917  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:34:01.917  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 10:34:01.918  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 10:34:01.921  5631  5631 D SprintDMHelper: simOperator: 
,11-24 10:34:01.922  5631  5631 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 10:34:01.924  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:34:01.924  5532  5580 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:34:01.924  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 10:34:01.929  3796  5798 I SystemUpdateService: showing system update notification
,11-24 10:34:01.931  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.931  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:34:01.931  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:34:01.931  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:34:01.931  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 10:34:01.934  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.934  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:34:01.934  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:34:01.934  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-24 10:34:01.934  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:34:01.934  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.935  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:01.938  5724  5735 D BtGatt.GattService: registerClient() - UUID=362ace5f-e3d8-4b15-9a79-60d3856b5d35
11-24 10:34:01.938  5724  5740 D BtGatt.GattService: onClientRegistered() - UUID=362ace5f-e3d8-4b15-9a79-60d3856b5d35, clientIf=5
11-24 10:34:01.939  5532  5542 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:34:01.940  5724  5753 D BtGatt.GattService: start scan with filters
,11-24 10:34:01.943  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:34:01.943  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.943  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:34:01.943  5724  5743 D BtGatt.ScanManager: handling starting scan
11-24 10:34:01.943  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.943  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:34:01.944  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:34:01.944  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.944  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:34:01.944  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 10:34:01.944  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.944  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.944  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.944  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.945  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:34:01.945  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.946  5724  5743 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@97271f7
,11-24 10:34:01.948  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.948  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:34:01.948  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.948  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.948  5532  5580 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 10:34:01.948  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.948  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:34:01.948  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:34:01.949  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:01.949  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:34:01.949  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:01.949  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 10:34:01.952  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 10:34:01.952  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.952  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.952  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:34:01.952  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:34:01.952  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.952  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:34:01.952  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:34:01.952  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.952  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.952  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.952  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:34:01.952  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.953  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:01.953  5724  5735 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:34:01.953  5724  5740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:34:01.953  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:01.953  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:34:01.954  5724  5743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:34:01.954  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:01.954  5724  5734 D BtGatt.GattService: stopScan() - queue size =1
11-24 10:34:01.955  5724  5752 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:34:01.955  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 10:34:01.955  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.955  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:34:01.955  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.955  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.956  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.956  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.956  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:34:01.956  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.956  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.956  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.956  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:34:01.956  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:34:01.957  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:34:01.957  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.959  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:34:01.959  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:34:01.960  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.960  5724  5743 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:34:01.960  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:34:01.960  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.960  5724  5743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 10:34:01.960  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.960  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:34:01.960  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:34:01.960  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:34:01.962  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:34:01.962  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:34:01.962  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:34:01.968  5724  5740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:34:01.969  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:01.969  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:01.969  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:01.969  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:01.970  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d7f00b removed from the list
11-24 10:34:01.960  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.970  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:01.970  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96bee8 removed from the list
11-24 10:34:01.970  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:34:01.970  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:34:01.970  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-24 10:34:01.970  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.970  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.970  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.971  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.971  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 10:34:01.971  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:34:01.971  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.971  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.972  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.972  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.972  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.972  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:01.972  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.973  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:01.973  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.973  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:01.973  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:01.973  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e96bee8 not in the list
11-24 10:34:01.973  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.973  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.974  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:34:01.974  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:01.975  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.976  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:01.976  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:01.976  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:01.976  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:01.976  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:01.976  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d57f3a6 removed from the list
11-24 10:34:01.976  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:01.976  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:01.976  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:01.976  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ca2901 removed from the list
11-24 10:34:01.977  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:34:01.977  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58c5583 added. We now have 3 listener(s)
11-24 10:34:01.977  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:34:01.979  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:01.979  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:01.979  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 10:34:01.979  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:01.979  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5208300 added. We now have 4 listener(s)
11-24 10:34:01.979  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:01.980  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:34:01.980   932   932 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-24 10:34:01.981  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:34:01.981  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c1f739 added. We now have 4 listener(s)
11-24 10:34:01.982  3796  3796 D SystemUpdateService: onDestroy
11-24 10:34:01.983  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:01.983  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:01.983  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:34:01.983  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:01.983  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:01.983  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:01.983  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ffd17e added. We now have 5 listener(s)
11-24 10:34:01.984  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:01.984  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:34:01.984  5724  5740 E BtGatt.ContextMap: Context not found for ID 5
11-24 10:34:01.984  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:34:01.984  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:34:01.984  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-24 10:34:01.984  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:34:01.984  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 10:34:01.986  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 10:34:01.991  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 10:34:01.991  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:01.992  5724  5743 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:34:01.994  3514  5808 I VacuumService: Vacuum at: now=1479980041994 tag=VacuumService
,11-24 10:34:01.996  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 10:34:01.996  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:34:01.996  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:34:01.997  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:34:01.997  5532  5580 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:34:01.997  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 10:34:02.000  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:02.000  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 10:34:02.001  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:34:02.001  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:34:02.001  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 10:34:02.003  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:34:02.003  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:34:02.007  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:02.007  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:34:02.007  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:34:02.007  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:34:02.007  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:34:02.007  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.008  5532  5580 D BluetoothAdapter: STATE_ON
,11-24 10:34:02.012  5724  5753 D BtGatt.GattService: registerClient() - UUID=b970b353-3f6d-4de4-8505-c455e55090c2
,11-24 10:34:02.012  5724  5740 D BtGatt.GattService: onClientRegistered() - UUID=b970b353-3f6d-4de4-8505-c455e55090c2, clientIf=5
,11-24 10:34:02.013  5532  5542 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 10:34:02.013  5724  5765 D BtGatt.GattService: start scan with filters
,11-24 10:34:02.015  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:34:02.015  5724  5743 D BtGatt.ScanManager: handling starting scan
11-24 10:34:02.015  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.015  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 10:34:02.015  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 10:34:02.015  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:34:02.015  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:34:02.015  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 10:34:02.015  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:34:02.015  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:34:02.015  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.016  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.016  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.016  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.016  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:34:02.017  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.019  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.019  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:34:02.019  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.019  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.020  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.020  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:34:02.020  5532  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 10:34:02.020  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:34:02.020  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:34:02.020  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:34:02.020  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:02.020  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.020  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:34:02.020  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:02.020  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:02.020  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58c5583 removed from the list
11-24 10:34:02.020  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.020  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettin,gs: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5208300 removed from the list
11-24 10:34:02.020  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:34:02.020  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.020  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:34:02.020  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.020  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.020  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 10:34:02.020  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.020  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:34:02.020  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.021  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.021  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.022  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.022  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:02.022  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:02.022  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.022  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.022  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5208300 not in the list
11-24 10:34:02.022  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.022  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.022  5724  5740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:34:02.022  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:34:02.022  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.022  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:34:02.022  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.022  5724  5743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:34:02.022  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:34:02.022  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:34:02.022  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.023  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.023  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.023  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:34:02.023  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.024  4940  5804 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-24 10:34:02.025  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:02.026  5724  5765 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:34:02.026  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:34:02.026  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:02.027  5724  5735 D BtGatt.GattService: stopScan() - queue size =1
11-24 10:34:02.028  5724  5752 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:34:02.028  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:34:02.028  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.028  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:34:02.028  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.029  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:34:02.029  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:34:02.029  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:34:02.029  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.029  5724  5743 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:34:02.029  5724  5743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 10:34:02.029  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:34:02.032  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.033  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.033  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:34:02.033  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.033  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.033  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:02.034  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:02.034  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.034  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:34:02.034  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ffd17e removed from the list
11-24 10:34:02.034  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:02.034  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:34:02.034  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:02.034  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:02.034  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:34:02.034  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c1f739 removed from the list
11-24 10:34:02.034  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.034  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:34:02.035  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c8f1fb added. We now have 3 listener(s)
11-24 10:34:02.035  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:34:02.035  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:34:02.035  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.035  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.035  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.035  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:34:02.035  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.035  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.036  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:02.036  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:02.036  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:02.036  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:02.036  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bb218 added. We now have 4 listener(s)
11-24 10:34:02.036  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:02.037  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:34:02.037  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.037  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:34:02.037  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.038  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ae5471 added. We now have 4 listener(s)
11-24 10:34:02.038  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.039  5724  5740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:34:02.039  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.039  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:02.039  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:02.039  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:02.039  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:02.039  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a9256 added. We now have 5 listener(s)
11-24 10:34:02.039  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:02.039  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:34:02.039  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:34:02.039  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:34:02.039  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:34:02.039  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 10:34:02.040  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 10:34:02.041  3514  5812 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-24 10:34:02.043  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:34:02.043  5532  5580 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:34:02.043  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 10:34:02.046  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:34:02.046  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.048  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:34:02.049  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.049  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:34:02.052  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:34:02.052  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:34:02.052  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 10:34:02.054  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:34:02.054  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.054  5724  5740 E BtGatt.ContextMap: Context not found for ID 5
11-24 10:34:02.056  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.057  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:34:02.057  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:34:02.057  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:34:02.057  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:34:02.057  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.058  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:02.060  5724  5752 D BtGatt.GattService: registerClient() - UUID=c0ea7c1e-2420-4329-b382-f7ee30da1850
11-24 10:34:02.061  5724  5740 D BtGatt.GattService: onClientRegistered() - UUID=c0ea7c1e-2420-4329-b382-f7ee30da1850, clientIf=5
11-24 10:34:02.061  5532  5543 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:34:02.061  5724  5753 D BtGatt.GattService: start scan with filters
11-24 10:34:02.064  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:34:02.064  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.064  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:34:02.064  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.064  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:34:02.064  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:34:02.064  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.064  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:34:02.064  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:34:02.064  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.064  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.065  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.065  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.065  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 10:34:02.065  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.065  5724  5743 D BtGatt.ScanManager: stopping BLe Batch
11-24 10:34:02.065  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:34:02.065  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.067  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.067  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:34:02.067  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.067  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.068  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.070  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 10:34:02.070  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.070  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:34:02.070  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:34:02.070  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:34:02.070  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:34:02.070  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:02.070  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.070  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:34:02.071  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:02.071  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:02.071  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c8f1fb removed from the list
11-24 10:34:02.071  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.071  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bb218 removed from the list
11-24 10:34:02.071  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:34:02.071  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.071  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:34:02.071  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.071  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.071  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.071  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 10:34:02.071  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.071  5532  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:34:02.071  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.071  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:34:02.071  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.071  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:34:02.072  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.072  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.073  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:02.073  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:02.073  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.073  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bb218 not in the list
11-24 10:34:02.073  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.073  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:34:02.073  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.074  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:02.074  5724  5753 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:34:02.075  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:34:02.075  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:34:02.075  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.076  5532  5580 D BluetoothAdapter: STATE_ON
11-24 10:34:02.076  5724  5743 D BtGatt.ScanManager: handling starting scan
11-24 10:34:02.076  5724  5765 D BtGatt.GattService: stopScan() - queue size =0
11-24 10:34:02.077  5724  5735 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.077  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.078  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.078  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:34:02.078  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:34:02.078  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:34:02.078  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.080  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.080  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:34:02.080  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.080  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.080  5724  5740 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:34:02.080  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:02.080  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.080  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:02.081  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.081  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:34:02.081  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a9256 removed from the list
11-24 10:34:02.081  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:02.081  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:34:02.081  5724  5743 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:34:02.081  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:02.081  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:02.081  5532  5532 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:34:02.081  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ae5471 removed from the list
11-24 10:34:02.081  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.081  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:34:02.081  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:34:02.081  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.081  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.081  5532  5532 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.081  5532  5532 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:34:02.081  5532  5532 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.081  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.081  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:34:02.081  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7da573 added. We now have 3 listener(s)
11-24 10:34:02.082  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.083  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:02.083  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.083  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:02.083  5532  5532 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:34:02.083  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:02.083  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:02.083  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daac30 added. We now have 4 listener(s)
11-24 10:34:02.083  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:02.083  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:34:02.084  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:34:02.084  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab220a9 added. We now have 4 listener(s)
11-24 10:34:02.086  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 10:34:02.086  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:34:02.086  5532  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:34:02.086  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:34:02.086  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f81962e added. We now have 5 listener(s)
11-24 10:34:02.086  5532  5580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:34:02.086  5532  5580 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:34:02.087  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:34:02.087  5532  5580 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:34:02.087  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:02.087  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:02.087  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:02.087  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7da573 removed from the list
11-24 10:34:02.087  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.087  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daac30 removed from the list
11-24 10:34:02.087  5532  5580 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:34:02.087  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.087  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:34:02.087  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.087  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.088  5724  5743 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:34:02.088  5724  5743 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 10:34:02.088  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.089  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.089  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.089  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:02.089  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:02.089  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.089  5532  5580 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daac30 not in the list
11-24 10:34:02.089  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.089  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.090  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.090  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.090  5532  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 10:34:02.090  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:34:02.090  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:34:02.090  3514  5809 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-24 10:34:02.090  5532  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:34:02.090  5532  5580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f81962e removed from the list
11-24 10:34:02.091  5532  5580 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:34:02.091  5532  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:34:02.091  5532  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:34:02.091  5532  5580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab220a9 removed from the list
11-24 10:34:02.091  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 10:34:02.091  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 10:34:02.092  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 10:34:02.092  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:34:02.092  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 10:34:02.092  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:34:02.093  3514  5809 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-24 10:34:02.098  5724  5740 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 10:34:02.098  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.102  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:34:02.102  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.103  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:34:02.107  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:34:02.107  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.108  5724  5740 E BtGatt.ContextMap: Context not found for ID 5
11-24 10:34:02.113  5724  5740 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 10:34:02.113  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.113  5724  5743 D BtGatt.ScanManager: stopping BLe Batch
11-24 10:34:02.118  5724  5740 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 10:34:02.118  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.119  5724  5743 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:34:02.120  3514  5809 W Uploader:  no longer exists, so no auth token.
11-24 10:34:02.124  5724  5740 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:34:02.124  5724  5740 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:34:02.126  3514  5812 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:34:02.193   932  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 10:34:02.210   932  3727 D ConnectivityService: reportNetworkConnectivity(101, true) by 10012
,11-24 10:34:02.222   932  3743 D ConnectivityService: reportNetworkConnectivity(101, true) by 10012
,11-24 10:34:02.225   932   943 D ConnectivityService: reportNetworkConnectivity(101, true) by 10012
,11-24 10:34:02.275   932  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 09:34:02 GMT], X-Android-Received-Millis=[1479980042274], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479980042229]}
,11-24 10:34:02.276   932  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-24 10:34:02.276   932  2910 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 10:34:02.276   932  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 10:34:02.276   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 10:34:02.276   932  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 10:34:02.277   932  2910 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 10:34:02.314   932  5782 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 09:34:02 GMT], X-Android-Received-Millis=[1479980042314], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479980042280]}
11-24 10:34:02.315   932  2910 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 10:34:02.315   932  2910 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-24 10:34:02.366   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:02.427  3514  5815 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:34:02.472  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:34:02.536  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:34:02.582  5532  5532 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:34:02.584  3514  5812 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:34:02.665  3514  5809 W Uploader:  no longer exists, so no auth token.
,11-24 10:34:02.679  3514  5815 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:34:02.775  3514  5812 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:34:02.840   932  2910 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 10:34:02.857  3514  5815 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:34:03.367   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 10:34:04.219  5532  5821 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 10:34:04.219  5532  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:04.590   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:34:05.025  5532  5821 W !!      : call onHalfStreamCopied
,11-24 10:34:05.025  5532  5821 I testCopyDataAndClose: closing input stream
,11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 10:34:05.800  5532  5821 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 10:34:09.797   932  2910 D ConnectivityService: handlePromptUnvalidated 101
,11-24 10:34:10.103  5532  5822 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:10.103  5532  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:12.103  5532  5580 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-24 10:34:12.103  5532  5580 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:12.103  5532  5580 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-24 10:34:12.145  5532  5822 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 10:34:12.145  5532  5822 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:12.145  5532  5822 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-24 10:34:12.225  5532  5823 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 10:34:12.225  5532  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:12.907   932  2908 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 10:34:13.840  5532  5823 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 10:34:17.975  5532  5824 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:17.975  5532  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:34:17.975  5532  5824 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:17.975  5532  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 10:34:17.975  5532  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 10:34:17.975  5532  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 10:34:17.975  5532  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 10:34:17.976  5532  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 10:34:17.976  5532  5824 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 10:34:17.976  5532  5824 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 10:34:17.976  5532  5824 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 10:34:17.976  5532  5824 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:17.976  5532  5824 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-24 10:34:17.978  5532  5580 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 10:34:17.981  5532  5825 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:17.981  5532  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 10:34:17.982  5532  5825 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-24 10:34:17.982  5532  5825 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:17.982  5532  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 10:34:17.982  5532  5825 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 10:34:17.982  5532  5825 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:34:17.982  5532  5825 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 10:34:17.987  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 10:34:17.987  5532  5580 I jxcore-log: 
,11-24 10:34:17.988  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 10:34:17.988  5532  5580 I jxcore-log: 
11-24 10:34:17.988  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 10:34:17.988  5532  5580 I jxcore-log: 
11-24 10:34:17.988  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 10:34:17.988  5532  5580 I jxcore-log: 
,11-24 10:34:17.989  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG UnitTest_app: 'Total duration:  91666'
11-24 10:34:17.989  5532  5580 I jxcore-log: 
,11-24 10:34:17.992  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 10:34:17.992  5532  5580 I jxcore-log: 
,11-24 10:34:17.996  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:34:17.996  5532  5580 I jxcore-log: 
,11-24 10:34:17.998  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:34:17.998  5532  5580 I jxcore-log: 
11-24 10:34:17.998  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 10:34:17.998  5532  5580 I jxcore-log: 
11-24 10:34:17.999  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 10:34:17.999  5532  5580 I jxcore-log: 
11-24 10:34:17.999  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:17.999  5532  5580 I jxcore-log: 
11-24 10:34:17.999  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:34:17.999  5532  5580 I jxcore-log: 
11-24 10:34:17.999  5532  5580 I jxcore-log: 2016-11-24 09:34:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:17.999  5532  5580 I jxcore-log: 
,11-24 10:34:18.000  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:34:18.000  5532  5580 I jxcore-log: 
11-24 10:34:18.000  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:34:18.000  5532  5580 I jxcore-log: 
11-24 10:34:18.001  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 10:34:18.001  5532  5580 I jxcore-log: 
11-24 10:34:18.001  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 10:34:18.001  5532  5580 I jxcore-log: 
,11-24 10:34:18.001  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:18.001  5532  5580 I jxcore-log: 
11-24 10:34:18.001  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:34:18.001  5532  5580 I jxcore-log: 
,11-24 10:34:18.001  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:18.001  5532  5580 I jxcore-log: 
11-24 10:34:18.002  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:34:18.002  5532  5580 I jxcore-log: 
11-24 10:34:18.002  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:18.002  5532  5580 I jxcore-log: 
,11-24 10:34:18.002  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:34:18.002  5532  5580 I jxcore-log: 
,11-24 10:34:18.002  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 10:34:18.002  5532  5580 I jxcore-log: 
,11-24 10:34:18.003  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 10:34:18.003  5532  5580 I jxcore-log: 
,11-24 10:34:18.003  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 10:34:18.003  5532  5580 I jxcore-log: 
11-24 10:34:18.003  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 10:34:18.003  5532  5580 I jxcore-log: 
,11-24 10:34:18.004  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 10:34:18.004  5532  5580 I jxcore-log: 
11-24 10:34:18.004  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 10:34:18.004  5532  5580 I jxcore-log: 
11-24 10:34:18.004  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 10:34:18.004  5532  5580 I jxcore-log: 
11-24 10:34:18.006  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:34:18.006  5532  5580 I jxcore-log: 
,11-24 10:34:18.006  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:34:18.006  5532  5580 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 10:34:18.006  5532  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:34:18.006  5532  5580 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 10:34:18.006  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:34:18.006  5532  5580 I jxcore-log: 
,11-24 10:34:18.006  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:18.006  5532  5580 I jxcore-log: 
11-24 10:34:18.007  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:34:18.007  5532  5580 I jxcore-log: 
11-24 10:34:18.007  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:18.007  5532  5580 I jxcore-log: 
11-24 10:34:18.007  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:34:18.007  5532  5580 I jxcore-log: 
,11-24 10:34:18.007  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:34:18.007  5532  5580 I jxcore-log: 
11-24 10:34:18.012  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 10:34:18.012  5532  5580 I jxcore-log: 
11-24 10:34:18.013  5532  5580 I jxcore-log: 2016-11-24 09:34:18 - WARN testUtils: 'myNameCallback not set!'
11-24 10:34:18.013  5532  5580 I jxcore-log: 
11-24 10:34:18.014  5532  5532 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,11-24 10:34:18.014  5532  5532 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 10:34:20.064  5532  5580 I jxcore-log: 2016-11-24 09:34:20 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 10:34:20.064  5532  5580 I jxcore-log: 
,11-24 10:34:20.066  5532  5580 I jxcore-log: 2016-11-24 09:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 10:34:20.066  5532  5580 I jxcore-log: 
,11-24 10:34:20.413  5532  5580 I jxcore-log: 2016-11-24 09:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 10:34:20.413  5532  5580 I jxcore-log: 
,11-24 10:34:20.426  5532  5580 I jxcore-log: 2016-11-24 09:34:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 10:34:20.426  5532  5580 I jxcore-log: 
,11-24 10:34:21.544  5532  5580 I jxcore-log: 2016-11-24 09:34:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 10:34:21.544  5532  5580 I jxcore-log: 
,11-24 10:34:21.731  5532  5580 I jxcore-log: 2016-11-24 09:34:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 10:34:21.731  5532  5580 I jxcore-log: 
,11-24 10:34:21.737  5532  5580 I jxcore-log: 2016-11-24 09:34:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 10:34:21.737  5532  5580 I jxcore-log: 
,11-24 10:34:21.742  5532  5580 I jxcore-log: 2016-11-24 09:34:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 10:34:21.742  5532  5580 I jxcore-log: 
,11-24 10:34:22.224  5532  5580 I jxcore-log: 2016-11-24 09:34:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 10:34:22.224  5532  5580 I jxcore-log: 
,11-24 10:34:22.268  5532  5580 I jxcore-log: 2016-11-24 09:34:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 10:34:22.268  5532  5580 I jxcore-log: 
,11-24 10:34:22.281  5532  5580 I jxcore-log: 2016-11-24 09:34:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 10:34:22.281  5532  5580 I jxcore-log: 
,11-24 10:34:22.285  5532  5580 I jxcore-log: 2016-11-24 09:34:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 10:34:22.285  5532  5580 I jxcore-log: 
,11-24 10:34:22.554  5532  5580 I jxcore-log: 2016-11-24 09:34:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 10:34:22.554  5532  5580 I jxcore-log: 
,11-24 10:34:22.680  5532  5580 I jxcore-log: 2016-11-24 09:34:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 10:34:22.680  5532  5580 I jxcore-log: 
,11-24 10:34:23.053  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 10:34:23.053  5532  5580 I jxcore-log: 
,11-24 10:34:23.061  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 10:34:23.061  5532  5580 I jxcore-log: 
,11-24 10:34:23.065  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 10:34:23.065  5532  5580 I jxcore-log: 
,11-24 10:34:23.071  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 10:34:23.071  5532  5580 I jxcore-log: 
,11-24 10:34:23.076  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 10:34:23.076  5532  5580 I jxcore-log: 
,11-24 10:34:23.105  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 10:34:23.105  5532  5580 I jxcore-log: 
,11-24 10:34:23.139  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 10:34:23.139  5532  5580 I jxcore-log: 
,11-24 10:34:23.147  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 10:34:23.147  5532  5580 I jxcore-log: 
,11-24 10:34:23.153  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 10:34:23.153  5532  5580 I jxcore-log: 
,11-24 10:34:23.168  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 10:34:23.168  5532  5580 I jxcore-log: 
,11-24 10:34:23.184  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 10:34:23.184  5532  5580 I jxcore-log: 
,11-24 10:34:23.190  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 10:34:23.190  5532  5580 I jxcore-log: 
,11-24 10:34:23.195  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 10:34:23.195  5532  5580 I jxcore-log: 
,11-24 10:34:23.208  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 10:34:23.208  5532  5580 I jxcore-log: 
,11-24 10:34:23.225  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 10:34:23.225  5532  5580 I jxcore-log: 
,11-24 10:34:23.240  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 10:34:23.240  5532  5580 I jxcore-log: 
,11-24 10:34:23.251  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 10:34:23.251  5532  5580 I jxcore-log: 
,11-24 10:34:23.263  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 10:34:23.263  5532  5580 I jxcore-log: 
,11-24 10:34:23.273  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 10:34:23.273  5532  5580 I jxcore-log: 
,11-24 10:34:23.286  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 10:34:23.286  5532  5580 I jxcore-log: 
,11-24 10:34:23.296  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 10:34:23.296  5532  5580 I jxcore-log: 
,11-24 10:34:23.303  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 10:34:23.303  5532  5580 I jxcore-log: 
,11-24 10:34:23.325  5532  5580 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 10:34:23.326  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 10:34:23.326  5532  5580 I jxcore-log: 
,11-24 10:34:23.356  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 10:34:23.356  5532  5580 I jxcore-log: 
,11-24 10:34:23.368   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:23.689  5532  5580 I jxcore-log: 2016-11-24 09:34:23 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 10:34:23.689  5532  5580 I jxcore-log: 
,11-24 10:34:24.369   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:25.370   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:26.371   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:27.372   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:34:28.373   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 10:34:41.777   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:34:53.374   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 10:34:53.374   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 10:35:03.375   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:04.377   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:05.378   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:06.380   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:07.381   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:08.382   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 10:35:13.383   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:14.384   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:15.386   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:16.387   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:17.389   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:18.390   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 10:35:21.782   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:35:28.391   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:29.392   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:30.394   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:31.395   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:32.396   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:33.397   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 10:35:41.783   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:35:48.398   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:49.399   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:50.401   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:51.402   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:52.404   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:35:53.405   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 10:35:56.533   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:35:59.564   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:36:13.406   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:36:14.407   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:36:15.408   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:36:16.409   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:36:17.410   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:36:18.411   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 10:36:21.788   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:36:38.906   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:36:41.791   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:36:41.921   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:36:43.411   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 10:36:43.412   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 10:36:58.413   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:36:59.414   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:00.416   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:01.417   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:01.793   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:37:02.418   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:03.419   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 10:37:08.420   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:09.421   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:10.422   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:11.424   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:12.425   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:13.425   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 10:37:23.427   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:24.428   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:25.429   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:26.430   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:27.432   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:28.432   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 10:37:41.794   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:37:43.433   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:44.434   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:45.435   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:46.437   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:47.438   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:37:48.438   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 10:37:51.518   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:37:54.549   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:38:01.796   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:38:08.440   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:38:09.441   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:38:10.443   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:38:11.444   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:38:12.445   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:38:13.446   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 10:38:21.797   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:38:38.447   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 10:38:38.448   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 10:38:39.957   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:38:41.799   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:38:42.991   932  2910 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:38:58.449   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:38:59.450   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:39:00.179  5532  5580 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 10:39:00.179  5532  5580 I jxcore-log: 
,11-24 10:39:00.424  5532  5580 I jxcore-log: 2016-11-24 09:39:00 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 10:39:00.424  5532  5580 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 10:39:00.424  5532  5580 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 10:39:00.424  5532  5580 I jxcore-log: emit@events.js:82:1
11-24 10:39:00.424  5532  5580 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 10:39:00.424  5532  5580 I jxcore-log: emit@events.js:82:1''
11-24 10:39:00.424  5532  5580 I jxcore-log: 
,11-24 10:39:00.426  5532  5580 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedClient: 'test client failed'
11-24 10:39:00.426  5532  5580 I jxcore-log: 
,11-24 10:39:00.434  5532  5580 I jxcore-log: 2016-11-24 09:39:00 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 10:39:00.434  5532  5580 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 10:39:00.434  5532  5580 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 10:39:00.434  5532  5580 I jxcore-log: emit@events.js:82:1
11-24 10:39:00.434  5532  5580 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 10:39:00.434  5532  5580 I jxcore-log: emit@events.js:82:1''
11-24 10:39:00.434  5532  5580 I jxcore-log: 
,11-24 10:39:00.435  5532  5580 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedClient: 'test client failed'
11-24 10:39:00.435  5532  5580 I jxcore-log: 
,11-24 10:39:00.438  5532  5580 I jxcore-log: 2016-11-24 09:39:00 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 10:39:00.438  5532  5580 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 10:39:00.438  5532  5580 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 10:39:00.438  5532  5580 I jxcore-log: emit@events.js:82:1
11-24 10:39:00.438  5532  5580 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 10:39:00.438  5532  5580 I jxcore-log: emit@events.js:82:1''
11-24 10:39:00.438  5532  5580 I jxcore-log: 
,11-24 10:39:00.439  5532  5580 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 10:39:00.439  5532  5580 I jxcore-log: 
,11-24 10:39:00.451   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:39:01.011  5836  5836 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 10:39:01.031  5836  5836 D AndroidRuntime: CheckJNI is OFF
,11-24 10:39:01.059  5836  5836 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 10:39:01.094  5836  5836 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 10:39:01.111  5836  5836 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 10:39:01.121   932   945 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 10:39:01.121   932   945 I ActivityManager: Killing 5532:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 10:39:01.231   932  3727 I WindowState: WIN DEATH: Window{4efba09 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 10:39:01.232   932  3083 D GraphicsStats: Buffer count: 2
11-24 10:39:01.232   932  2909 D WifiService: Client connection lost with reason: 4
,11-24 10:39:01.249   932   945 W ActivityManager: Force removing ActivityRecord{4cbd6f1 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 10:39:01.289   932   955 I art     : Starting a blocking GC Explicit
,11-24 10:39:01.296   932  3506 W ActivityManager: Spurious death for ProcessRecord{c60e71b 0:com.test.thalitest/u0a77}, curProc for 5532: null
,11-24 10:39:01.326   932  3769 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5532 uid 10077
,11-24 10:39:01.323  3769  3769 W Binder_B: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28177]" dev="sockfs" ino=28177 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 10:39:01.323  3769  3769 W Binder_B: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28177]" dev="sockfs" ino=28177 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 10:39:01.327  3593  3593 I Keyboard.Facilitator: onFinishInput()
,11-24 10:39:01.399  3904  5849 I MicroRecognitionRnrImpl: Starting detection.
,11-24 10:39:01.400  3904  5850 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@4df13d2
,11-24 10:39:01.404   514  5852 I AudioFlinger: AudioFlinger's thread 0xf1e80000 ready to run
11-24 10:39:01.406   514  2930 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-24 10:39:01.408   932   955 I art     : Explicit concurrent mark sweep GC freed 128062(9MB) AllocSpace objects, 84(2MB) LOS objects, 33% free, 29MB/44MB, paused 2.284ms total 118.850ms
,11-24 10:39:01.410  3904  5850 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@4df13d2
,11-24 10:39:01.420   514  5852 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-24 10:39:01.420   514  5852 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-24 10:39:01.420   514  5852 I ACDB-LOADER: ACDB AFE returned = -19
11-24 10:39:01.420   514  5852 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
,11-24 10:39:01.420   514  5852 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
,11-24 10:39:01.420   514  5852 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-24 10:39:01.428   514  5852 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-24 10:39:01.430   932   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 10:39:01.431  5836  5836 I art     : System.exit called, status: 0
,11-24 10:39:01.432  5836  5836 I AndroidRuntime: VM exiting with result code 0.
,11-24 10:39:01.437   932   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 10:39:01.448  3593  3593 I Keyboard.Facilitator: resetDictionaries() : en_US
11-24 10:39:01.448  5724  5724 D BluetoothMapAppObserver: onReceive
11-24 10:39:01.448  5724  5724 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 10:39:01.451  4001  4113 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-24 10:39:01.452   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:39:01.460   932  2874 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 10:39:01.475  3593  5857 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 10:39:01.478  3593  5857 I Decoder : createOrResetDecoder
,11-24 10:39:01.511  3904  3904 I HotwordWorkerImpl: onReady
,11-24 10:39:01.516  3748  3748 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 10:39:01.518  3514  3514 I ConfigService: onCreate
,11-24 10:39:01.522  3330  5861 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 10:39:01.531   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 10:39:01.536  3514  3514 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-24 10:39:01.536  3514  3514 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-24 10:39:01.538  3593  5857 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 10:39:01.551  3796  5865 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-24 10:39:01.552  3796  5865 D AccountUtils: Clearing selected account for com.test.thalitest
,11-24 10:39:01.567    21    21 W kworker/3:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:39:01.567  3796  5865 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-24 10:39:01.580    21    21 W kworker/3:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:39:01.586  3796  3796 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-24 10:39:01.586  3796  3796 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-24 10:39:01.591  3796  3796 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-24 10:39:01.591  3796  3796 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-24 10:39:01.596  3796  5870 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
,11-24 10:39:01.597  3796  5870 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,11-24 10:39:01.598  3796  5870 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
11-24 10:39:01.598  3796  5870 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
11-24 10:39:01.599  3796  5870 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-24 10:39:01.599  3796  5870 E AndroidRuntime: Process: com.google.android.gms, PID: 3796
11-24 10:39:01.599  3796  5870 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:39:01.599  3796  5870 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 10:39:01.602  3593  5857 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-24 10:39:01.603    21    21 W kworker/3:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:39:01.617   751   751 W Binder_3: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[14906]" dev="sockfs" ino=14906 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:39:01.619  3330  5861 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,11-24 10:39:01.620  3330  5861 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-24 10:39:01.620  3330  5861 E AndroidRuntime: Process: android.process.acore, PID: 3330
11-24 10:39:01.620  3330  5861 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:39:01.620  3330  5861 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 10:39:01.617   751   751 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[14906]" dev="sockfs" ino=14906 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:39:01.620   752   752 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[15913]" dev="sockfs" ino=15913 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 10:39:01.620   752   752 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[15913]" dev="sockfs" ino=15913 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:39:01.621  3593  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-24 10:39:01.621  3593  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-24 10:39:01.622   932  5878 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-24 10:39:01.625  3904  5875 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
11-24 10:39:01.628   932  5879 E DropBoxManagerService: Can't write: system_app_crash
11-24 10:39:01.628   932  5879 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:39:01.628   932  5879 E DropBoxManagerService: 	... 5 more
11-24 10:39:01.628  3796  5880 I GMPM-SVC: App measurement is starting up
11-24 10:39:01.629  3593  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-24 10:39:01.629  3593  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-24 10:39:01.630  3593  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,11-24 10:39:01.630  3593  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-24 10:39:01.630  3763  4381 E ReflectionEngine: Failed to save models
11-24 10:39:01.630  3763  4381 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:39:01.630  3763  4381 E ReflectionEngine: 	... 16 more
,11-24 10:39:01.634  3593  5857 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-24 10:39:01.634  3593  5857 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-24 10:39:01.634  3593  5857 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-24 10:39:01.634  3593  5857 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-24 10:39:01.634  3593  5857 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-24 10:39:01.634  3593  5857 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-24 10:39:01.647  3796  5880 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-24 10:39:01.647  3796  5880 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-24 10:39:01.653  3904  5875 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-24 10:39:01.657   932  3722 I ActivityManager: Start proc 5883:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,11-24 10:39:01.659  3763  4381 E ObservedEventLogger: Failed to write the stream file
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2439: open failed: EROFS (Read-only file system)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:39:01.659  3763  4381 E ObservedEventLogger: 	... 16 more
,11-24 10:39:01.660  3763  4381 E ObservedEventLogger: Failed to write the stream file
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2440: open failed: EROFS (Read-only file system)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:39:01.660  3763  4381 E ObservedEventLogger: 	... 16 more
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: Failed to write the stream file
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2441: open failed: EROFS (Read-only file system)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.a,pps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	... 16 more
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: Failed to write the stream file
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2442: open failed: EROFS (Read-only file system)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor,.java:269)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:39:01.661  3763  4381 E ObservedEventLogger: 	... 16 more
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: Failed to write the stream file
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2443: open failed: EROFS (Read-only file system)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:39:01.662  3763  4381 E ObservedEventLogger: 	... 16 more
11-24 10:39:01.678   932   942 I ActivityManager: Start proc 5893:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-24 10:39:01.683  3904  5875 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
11-24 10:39:01.684  3904  5875 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
11-24 10:39:01.684  3904  5875 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 3904
11-24 10:39:01.684  3904  5875 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:39:01.684  3904  5875 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 10:39:01.685  3796  3796 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-24 10:39:01.696  3796  5872 W BaseAppContext: Using Auth Proxy for data requests.
11-24 10:39:01.700  3796  5872 W BaseAppContext: Using Auth Proxy for data requests.
11-24 10:39:01.717   932   945 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{743da38 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{2582aaa 3796 com.google.android.gms/10012/u0 remote:9448995}: process crashing
11-24 10:39:01.726   932   942 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3796 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-24 10:39:01.774  3796  5869 W DriveInitializer: Awaiting to be initialized
,11-24 10:39:01.774  3796  5911 W DriveInitializer: Background init thread started
,11-24 10:39:01.799   932  2908 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:39:01.989   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
